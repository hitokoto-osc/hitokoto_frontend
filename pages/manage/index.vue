<template>
  <manage-layout :menu-opened="menuOpened" :menu-selected="menuSelected">
    <h1>状态概览</h1>
  </manage-layout>
</template>
<style lang="less">

</style>

<script>
import manageLayout from '~/components/manageLayout.vue'
export default {
  components: {
    manageLayout
  },
  data() {
    return {
      menuOpened: [],
      menuSelected: ['overview']
    }
  },
  head() {
    return {
      title: '状态概览 - 管理面板'
    }
  }
}
</script>
