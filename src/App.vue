<template>
    <NavBar></NavBar>
    <div class="container">
        <router-view></router-view>
    </div>
</template>
  
<script setup lang='ts'>
    import NavBar from './components/NavBar.vue'
</script>
<style>
  
</style>