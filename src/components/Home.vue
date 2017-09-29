<template>
  <div class="intro">
    <div>
      <p>
        Je <b>crée</b><br/>
        des <b>sites web</b>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="stylus">
  .intro
    size 100vh

    div
      align(c)
      font-size 60px
      text-align center

      +tablet()
        font-size 40px

      +mobile()
        font-size 28px
</style>
