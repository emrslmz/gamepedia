<template>
  <div>
    <the-header />
    <home-page v-if="this.$route.name === 'HomePage'" />
    <router-view />
    <the-footer />
  </div>
</template>

<script>
export default {
  name: 'HomePageView',
  components: {
    TheHeader: () => import('@/modules/main/home/layouts/TheHeader.vue'),
    HomePage: () => import('@/modules/main/home/components/HomePage.vue'),
    TheFooter: () => import('@/modules/main/home/layouts/TheFooter.vue'),
  },
};
</script>
