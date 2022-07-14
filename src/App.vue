<template>
<!-- //Components -->
  <HeaderBar />
  <ContentPage/>
</template>

<script setup lang="ts">
//import
import HeaderBar from './components/HeaderBar.vue';
import ContentPage from './components/Content/ContentPage.vue';


</script>

<style lang="scss">

.container{
  width: 90%;
  max-width: 1200px;
  margin: 0px auto;
}

a{
  text-decoration: none;
}
</style>
