<template>
  <div class="classify-wrapper">
   <div class="search-btn">
    <van-icon name="search" />
    <div>苹果特价1元/斤</div>
   </div>
   <oneTab />
  </div>
</template>

<script>
import OneTab from '@/components/oneTab.vue';

export default {
  components: {
    OneTab,
  },
};
</script>

<style lang="less" scoped>
   .classify-wrapper {
     width: 375px;
     .search-btn {
       width: 335px;
       height: 33px;
       background-color: #eee;
       margin: 11px auto 0;
       display: flex;
       justify-content: center;
       align-items: center;
       font-size: 14px;
       border-radius: 10px;
       color: #a1a1a1;
     }
   }
</style>
