<script setup lang="ts">
//import 
import ContentSlider from "./ContentSlider.vue";
import BoxCard from "./BoxCard.vue";
</script>
<template>
  <main>
    <div class="container">

      <div class="content">
        <h1 class="title">Marketing</h1>
        <!-- //Components -->
        <ContentSlider /> <!-- //Slider -->
        <BoxCard/> <!-- //Box cards -->
      </div>

    </div>

  </main>
</template>

<style lang="scss">
//Content
.content {
  .title {
    font-size: 45px;
    font-weight: bolder;
  }
}
</style>
