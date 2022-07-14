<script setup lang="ts">

</script>

<template>
    <section>
        <h1 style="text-align:center">What We Offer</h1>
        <div class="container">
            
            <div class="card">
                <!-- //Box -->
                <div style="background: #f1f1f1;" class="box">
                    <h1>Design</h1>
                    <span>
                        Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.
                    </span>
                </div>
                <div style="background:#9e9e9e; color: white;" class="box">
                    <h1>Branding</h1>
                    <span>
                        Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.
                    </span>
                </div>
                <div style="background: #616161; color: white;" class="box">
                    <h1>Consultation</h1>
                    <span>
                        Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.
                    </span>
                </div>
                <div style="background: black; color:white;" class="box">
                    <h1>Promises</h1>
                    <span>
                        Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse sodales pellentesque elementum.
                    </span>
                </div>
                <!--  -->
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.card{
    display: flex;
    align-items: center;
    justify-content: center;
   
   .box{
    display: flex;
    flex-direction: column;
    width: 300px;
    height: 200px;
    padding: 10px;
    box-sizing: border-box;
    border: 1px solid #f1f1f1;
    margin-bottom: 10px;
   }
}

//REsponsive
@media only screen and (max-width: 800px) {
  .card{
    flex-direction: column !important;
    .box{
        width: 90%;
        height: 130px;
    }
  }
}
</style>