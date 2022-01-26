<template>
  <div>
    <qualsiasinomebastachenonsiatitle/>
  </div>
</template>

<script>
import qualsiasinomebastachenonsiatitle from './qualsiasinomebastachenonsiatitle.vue'
export default {
  name: 'hero',
  components: { 
    qualsiasinomebastachenonsiatitle 
    },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  div {
    background-color: lightgrey;
    margin: 0 auto;
    width: 80%;
    height: 100px;
    text-align: center;
    line-height: 100px;
  }
</style>