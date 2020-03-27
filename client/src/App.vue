<template>
  <div id="app">
  <app-nav> </app-nav>

    <router-view class="container"/>
  </div>
</template>

<script>
import AppNav from '@/components/AppNav.vue';

export default {
  components: {
    AppNav,
  },
};

</script>

<style lang="scss">


#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
