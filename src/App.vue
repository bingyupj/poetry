<template>
  <router-view/>
</template>

<script>
  export default {
    name: 'app',
    data() {
      return {

      }
    },
    methods: {
    },
    components: {
    },
    created() {
      console.log('app初始化!')
    }
  }
</script>

<style lang="scss">
  @import '../static/css/index.scss'; // 全局自定义的css样式
</style>
