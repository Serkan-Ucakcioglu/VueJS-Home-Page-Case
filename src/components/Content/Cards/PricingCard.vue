<script setup lang="ts"></script>

<template>
  <section>
    <div class="container">
      <div class="pricing">
          <!-- head title -->
        <div class="head-title">
          <h1>Pricing Plans</h1>
          <h3>Choose a pricing plan that fits your needs.</h3>
        </div>
        
         <div class="pricing-list">
               <!-- Pricing Card -->
          <ul class="pricing-card">
            <li style="background: black; color: white;"><h1>Basic</h1></li>
            <li>10GB Storage</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li style="font-size: 20px; font-weight: bold">
              $ 10
              <p>Per month</p>
            </li>  <!-- Pricing Card -->
             
               <!-- sign up btn -->
            <button class="sign-up">Signup</button>
          </ul>
         <ul class="pricing-card">
            <li style="background: black; color: white;"><h1>Basic</h1></li>
            <li>10GB Storage</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li style="font-size: 20px; font-weight: bold">
              $ 10
              <p>Per month</p>
            </li>  <!-- Pricing Card -->
             
               <!-- sign up btn -->
            <button class="sign-up">Signup</button>
          </ul>
           <ul class="pricing-card">
            <li style="background: black; color: white;"><h1>Basic</h1></li>
            <li>10GB Storage</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li>10 Emails</li>

            <li style="font-size: 20px; font-weight: bold">
              $ 10
              <p>Per month</p>
            </li>  <!-- Pricing Card -->
             
               <!-- sign up btn -->
            <button class="sign-up">Signup</button>
          </ul>
         </div>
      </div>
      
    </div>
  </section>
</template>

<style lang="scss" scoped>
.pricing {
    display: flex;
    flex-direction: column;
    align-items: center;
  .head-title {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }


 //pricing card
   .pricing-list{
    display: flex;
    justify-content: space-around;
     .pricing-card {
      width: 350px;
      display: flex;
      flex-direction: column;
      align-items: center;
      border: 1px solid gray;
      padding: 0;
      margin-right: 10px;
      li {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        border-bottom: 1px solid gray;
        text-align: center;
        margin-bottom: 10px;
        padding: 10px;
        box-sizing: border-box;
      }
    }
    //button
    .sign-up{
        padding: 10px;
        border:none;
        background:#4CAF50;
        color: white;
        margin-bottom: 10px;
        cursor: pointer;
    }
   }
  
}

//REsponsive
@media only screen and (max-width: 800px) {
  .pricing-list{
    flex-direction: column !important;
    justify-content: center !important;
    align-items: center !important;
    .pricing-card{
        margin-bottom: 10px;
        
    }
  }
}
</style>
