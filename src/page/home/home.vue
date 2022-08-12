<template>
  <div class="home-page">
    首页
  </div>
</template>

<script>
  import { outLogin } from '@/utils/userCenter'
  export default {
    name: "home",
    data () {
      return {
        contentHeight: {},
        scrollTop: 0
      }
    },
    components: { comHeader },
    methods: {
      logout () {
        outLogin()
      }
    },
    mounted () {
    },
    destroyed () {
      
    }
  }
</script>

<style scoped lang="scss">
</style>