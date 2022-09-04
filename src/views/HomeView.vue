<template>
  <div class="home">
    <LogoComponent />
  </div>
</template>

<script>
import LogoComponent from '@/components/LogoComponent.vue';
// @ is an alias to /src

export default {
    name: "HomeView",
    components: { LogoComponent }
}
</script>
<style>
  .home{
    display: flex;
    flex-direction: column;
    
  }
</style>
