<script setup lang="ts">
//import 
import InfoCard from "./Cards/InfoCard.vue";
import PricingCard from "./Cards/PricingCard.vue";
import BoxCard from "./Cards/BoxCard.vue";
import ContentSlider from "./ContentSlider.vue";

</script>
<template>
  <main>
    <div class="container">

      <div class="content">
        
        <!-- //Components -->
        <ContentSlider /> <!-- //Slider -->
        <BoxCard/> <!-- //Box cards -->
        <PricingCard/> <!-- //Pricing Plans -->
        <InfoCard/>
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
