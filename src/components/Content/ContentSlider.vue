<script setup lang="ts">
import { VueperSlides, VueperSlide } from 'vueperslides'
import 'vueperslides/dist/vueperslides.css'

const slides = [
 {
    // You can also provide a URL for the image.
    image: ('https://www.w3schools.com/w3images/sound.jpg')
  },
  {
    // You can also provide a URL for the image.
    image: ('https://gezginsitesi.com/wp-content/uploads/2019/02/eymir-kapak.jpg')
  },
  {
    image: ('https://static.wixstatic.com/media/8af23d_0fd9fa14c2034fc6a5ca1fb1a97fc317~mv2.jpg/v1/fill/w_726,h_312,al_c,lg_1,q_80,enc_auto/8af23d_0fd9fa14c2034fc6a5ca1fb1a97fc317~mv2.jpg')
  },
  {
    image: ('https://gaiadergi.com/wp-content/uploads/2015/08/maldivler3.jpg')
  }
]
</script>

<template>
   <vueper-slides fade :touchable="true">
  <vueper-slide
    v-for="(slide, i) in slides"
    :key="i"
    :image="slide.image"
    />
</vueper-slides>
</template>

<style lang="scss">
</style>