<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="stylus">
  @import 'jeet'
  @import 'rupture'
  @import 'kouto-swiss'

  @import url('https://fonts.googleapis.com/css?family=Titillium+Web:300,400,700')

  meyer-reset()
  normalize()

  body
    background-color #f5f5f5
    color #343332
    font-family 'Titillium Web', sans-serif

  #app
    display block
</style>
