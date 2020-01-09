<template>
  <body>
    <top></top>
    <main class="main-content container">
      <router-view></router-view>
    </main>
    <bottom></bottom>
  </body>
</template>

<script>
  import top from '@/components/layouts/top'
  import bottom from '@/components/layouts/bottom'

  export default {
    name: 'layout-full',
    components: {
      'top': top,
      'bottom': bottom
    }
  }
</script>

<style scoped>
  .main-content {
    min-height: 800px;
  }
</style>