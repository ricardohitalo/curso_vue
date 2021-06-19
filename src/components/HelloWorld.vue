<template>
    <div>
      <h1>My name is {{ name }}</h1>
    </div> 
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {    
    name: 'Ricardo'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  text-align: center;
}
</style>
