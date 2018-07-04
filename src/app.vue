<template>
  <h1>{{title}}</h1>
</template>

<script>
export default {
  name: '',
  data: function(){
    return {
      title: 'Ahoy there'
    }
  },
  props: {
  }
}
</script>

<style scoped>
  h1{
    color: red
  }
</style>