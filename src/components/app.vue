<template>
    <div>
        <h2>333</h2>
      <!-- <child v-on:parentq="parentSend"></child> -->
    </div>
  </template>
  
  <script>
    import child from './HelloWorld.vue';
  export default {
    name: 'app5',
    components:{
      child
    },
    data(){
      return{
  
      }
    },
    methods:{
      parentSend(value){
          debugger
        console.log('value',value)
  
      }
    }
  }
  </script>
  
  <style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  </style>
  