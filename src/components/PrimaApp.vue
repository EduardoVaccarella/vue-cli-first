<template>
  <div>
    <h1>
      La mia prima App con Vue CLI!
    </h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div {
  display: flex;
  justify-content: center;

  h1 {
    color: grey;
  }
}
</style>
