<template>
  <div>
      <img src="../assets/SUPERMAN.jpg" alt="">

  </div>
    
</template>

<script>
export default {
  name: 'JumbotronHero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  img{
    width: 100%;
  }
</style>