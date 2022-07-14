<script setup lang="ts">
import {ref} from "vue"

const isShow = ref(false);
</script>
<template>
  <header>
    <div class="container">
<div class="hamburger-btn" @click="isShow = !isShow">
            <svg
              class="open-menu"
              v-show="isShow == false"
              viewBox="0 0 100 80"
              width="25"
              height="25"
            >
              <rect width="100" height="20"></rect>
              <rect y="30" width="100" height="20"></rect>
              <rect y="60" width="100" height="20"></rect>
            </svg>
            <svg
              v-show="isShow == true"
              class="close-menu"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path
                d="M24 20.188l-8.315-8.209 8.2-8.282-3.697-3.697-8.212 8.318-8.31-8.203-3.666 3.666 8.321 8.24-8.206 8.313 3.666 3.666 8.237-8.318 8.285 8.203z"
              />
            </svg>
          </div>
      <nav :class="{active: isShow}" class="navigation-list">
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
  min-height: 100px;
  .container{
    .navigation-list{
      display: flex;
      justify-content: space-around;
      align-items: center;
      min-height: 100px;
      
      a{
        font-size: 17px;
        color: black;
        font-weight: bolder;
        padding: 15px;
        &:hover{
           border: 1px solid gray;
           background: gray;
           color: white;
           
        }
        
      }
     
      
    }
     .hamburger-btn{
        display: none;
      }
  }
}
@media only screen and (max-width: 800px) {
 .navigation-list{
  display: none !important;
flex-direction: column;
justify-content: center !important;
align-items: center !important;
padding: 15px;
box-sizing: border-box;

a{
  width: 100%;
  border: 1px solid black;
  border-radius: 4px;
  margin-bottom: 15px;
}
 }
  .hamburger-btn{
    display: flex !important;
    justify-content: flex-end;
    align-items:center ;
   min-height: 100px;
  }
}
.active{
  display: flex !important; 
}

</style>
