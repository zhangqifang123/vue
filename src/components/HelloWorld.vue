<template>
  <div class="hello">
    <button @click='send'>子组件</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '1112'
    }
  

  },
  methods:{
    send(){
      debugger
      this.$emit('parentq',this.msg)
    }
    
  }
  




}
</script>

<style scoped>

</style>
