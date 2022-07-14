<script setup lang="ts"></script>
<template>
  <header>
    <div class="container">
      <nav class="navigation-list">
        <a href="#">Home</a>
        <a href="#">Plans</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
      </nav>
    </div>
  </header>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header{
  background: #f1f1f1;
  height: 70px;
  .container{
    .navigation-list{
      height: 70px;
      display: flex;
      justify-content: space-around;
      align-items: center;
      
      a{
        font-size: 17px;
        color: black;
        font-weight: bolder;
        
      }
      
    }
  }
}
</style>
