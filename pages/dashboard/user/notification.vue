<template>
  <dashboard-layout :menu-selected="menuSelected" :menu-opened="menuOpened">
    <h1>消息通知</h1>
  </dashboard-layout>
</template>
<style lang="less">
</style>
<script>
import dashboardLayout from '~/components/dashboardLayout.vue'
export default {
  components: {
    dashboardLayout
  },
  data() {
    return {
      menuSelected: ['user-notification'],
      menuOpened: ['user']
    }
  },
  head() {
    return {
      title: '消息通知'
    }
  }
}
</script>
