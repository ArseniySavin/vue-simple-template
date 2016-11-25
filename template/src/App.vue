<template lang="pug">
  div
    h1 \{{ message }}
</template>

<script>
export default {
  data() {
    return {
      message: 'Привет Vue!'
    }
  }
}
</script>

<style lang="sass">
  body
    padding: 0
    margin: 0
    font-family: 'Open Sans', Helvetica, sans-serif
  h1
    display: block
    position: absolute
    width: 100%
    height: 100px
    top: 50%
    margin: -50px 0 0 0
    font-size: 54px
    line-height: 64px
    font-weight: 300
    color: #525255
    text-align: center
</style>
