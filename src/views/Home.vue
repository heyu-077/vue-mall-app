<template>
  <div>
      <router-view></router-view>
      <tabBar />
  </div>
</template>

<script>
import TabBar from '@/components/tabBar.vue';

export default {
  components: {
    TabBar,
  },
};
</script>

<style>

</style>
