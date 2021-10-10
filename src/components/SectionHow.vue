<template>
  <section class="section-how">
    <div class="container">
      <span class="subheading">How it works</span>
      <h2 class="heading-secondary">
        Your daily dose of health in 3 simple steps
      </h2>
    </div>
    <div class="container grid grid--2-cols grid-center-v">
      <div class="step-text-box">
        <p class="step-number">01</p>
        <h3 class="heading-tertiary">Tell us what you like (and what not)</h3>
        <p class="step-description">
          Never again waste time thinking about what to eat! Omnifood AI will
          create a 100% personalized weekly meal plan just for you. It makes
          sure you get all the nutrients and vitamins you need, no matter what
          diet you follow! 
        </p>
      </div>
      <div class="step-img-box">
        <img
          src="../assets/img/app/app-screen-1.png"
          alt="iphone app prefences"
          class="step-img"
        />
      </div>

      <div class="step-img-box">
        <img
          src="../assets/img/app/app-screen-2.png"
          alt="iphone app prefences"
          class="step-img"
        />
      </div>
      <div class="step-text-box">
        <p class="step-number">02</p>
        <h3 class="heading-tertiary">Approve your weekly meal plan</h3>
        <p class="step-description">
          Once per week, approvethe meal plan generated for you by Omnifood AI.
          You can change ingredients, swap entire meals, or even add your own
          recipes.
        </p>
      </div>
      <div class="step-text-box">
        <p class="step-number">03</p>
        <h3 class="heading-tertiary">
          Receive meals at convenient time
        </h3>
        <p class="step-description">
          Best chefs in town will cook your selected meal every day, and we will
          deliver it to your door whenever works best for you. You can change
          delivery schedule and address daily!
        </p>
      </div>
      <div class="step-img-box">
        <img
          src="../assets/img/app/app-screen-3.png"
          alt="iphone app prefences"
          class="step-img"
        />
      </div>
    </div>
  </section>
</template>
<style>
.section-how {
  padding: 9.6rem 0;
}
.step-number{
  font-size: 9.8rem;
  font-weight: 600;
  color: #ddd;
  margin-bottom: 1.2rem;
}
.step-description {
  font-size: 1.8rem;
  line-height: 1.8;
}
.step-img-box{
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
.step-img-box::before, .step-img-box::after{
  content: "";
  display: block;
  border-radius: 50%;  
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.step-img-box::before{
  width: 60%;
  background-color: #fdf2e9;
  /* height: 60%; */
  padding-bottom: 60%;
  z-index: -2;
}
.step-img-box::after{
  width: 45%;
  padding-bottom: 45%;
  background-color: #fae5d3;
  z-index: -1;
}
.step-img {
  width: 35%;
}
</style>
