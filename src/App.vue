<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <NavBar/>
    <RouterView/>
  </div>
</template>

<script>
import { RouterView } from 'vue-router';
import NavBar from './components/NavBar.vue';

export default {
    setup() {
        return {};
    },
    components: { NavBar }
}
</script>

<style lang="scss" scoped>

</style>