<template>
  <div>
    <h2>helloworld</h2>
    <h2>{{question}} </h2>
    <input type="text" v-model="question"> <input type="text" v-model="question">
    <button @click="clear">Reset</button>
  </div>

</template>

<script>
export default {
data() {
    return {
      question: '',
      answer: 'login'
    }
  },
  methods:{
        clear(){
               this.question=''

        }
  }
}
</script>

<style>

</style>