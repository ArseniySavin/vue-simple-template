<template lang="jade">
    h1 {{ message }}
</template>

<script>
    export default {
        data() {
            return {
                message: 'Пора работать!'
            }
        }
    }
</script>

<style lang="sass">
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