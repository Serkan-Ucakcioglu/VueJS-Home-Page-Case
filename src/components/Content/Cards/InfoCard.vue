<script setup lang="ts"></script>

<template>
  <section>
    <div class="container">
      <div class="card-list">
        <!-- Card title -->
        <div class="card-title">
          <h1>Who We Are</h1>
        </div>
        <!-- Cards -->
        <div class="cards">
          <div class="card">
            <img src="https://www.w3schools.com/w3images/team1.jpg" alt="" />
            <div class="card-info">
              <h1>Jane Doe</h1>
              <span>CEO & Founder </span>
              <p>
                Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse
                sodales pellentesque elementum.
              </p>
              <button class="contact">Contact</button>
            </div>
          </div>

          <!-- Cards -->
          <div class="card">
            <img src="https://www.w3schools.com/w3images/team2.jpg" alt="" />
            <div class="card-info">
              <h1>Mike Ross</h1>
              <span>Art Director </span>
              <p>
                Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse
                sodales pellentesque elementum.
              </p>
              <button class="contact">Contact</button>
            </div>
          </div>

          <!-- Cards -->
          <div class="card">
            <img src="https://www.w3schools.com/w3images/team3.jpg" alt="" />
            <div class="card-info">
              <h1>John Doe</h1>
              <span>Designer </span>
              <p>
                Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse
                sodales pellentesque elementum.
              </p>
              <button class="contact">Contact</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss">
section {
  margin-bottom: 10px;
  .card-list {
    display: flex;
    flex-direction: column;
    //<!-- Card title -->
    .card-title {
      text-align: center;
      h1 {
        font-size: 30px;
      }
    }
    //cards
    .cards {
      display: flex;
      justify-content: space-around;
      .card {
        width: 330px;
        -webkit-box-shadow: -1px -2px 15px 4px rgba(0, 0, 0, 0.75);
        -moz-box-shadow: -1px -2px 15px 4px rgba(0, 0, 0, 0.75);
        box-shadow: -1px -2px 15px 4px rgba(0, 0, 0, 0.75);
        margin-right: 10px;
        
        img {
          width: 100%;
          height: 200px;
        }
        .card-info {
          padding: 10px;
          box-sizing: border-box;
          span {
            color: gray;
          }
          p {
            color: black;
          }
          .contact {
            width: 100%;
            height: 35px;
            background: #f1f1f1;
            color: black;
            border: none;
            cursor: pointer;
            &:hover {
              background: gray;
              color: white;
            }
          }
        }
      }
    }
  }
}
@media only screen and (max-width: 600px) {
  .cards{
    display: flex;
    flex-direction: column !important;
    align-items: center !important;
    .card{
      margin-bottom: 20px !important;
    }
  }
}
</style>
