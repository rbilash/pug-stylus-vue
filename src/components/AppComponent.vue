<template lang="pug">
  div 
    p Hello {{ who }}
</template>

<script>
    export default {
        data () {
            return {
                who: "World"
            }
        }
    }
</script>

<style lang="stylus" scoped>
  div
    p
      color: red
</style>