<script setup lang="ts">
//import
import HeaderBar from './components/HeaderBar.vue';
import ContentPage from './components/Content/ContentPage.vue';
import FooterBar from './components/FooterBar.vue';


</script>
<template>
<!-- //Components -->
  <HeaderBar />
  <ContentPage/>
  <FooterBar/>
</template>



<style lang="scss">

.container{
  width: 90%;
  max-width: 1200px;
  margin: 0px auto;
}



a{
  text-decoration: none;
}
ul,li{
  list-style: none;
}
</style>
