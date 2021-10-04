<template>
  <div>
    <Header/>
    <section class="section-hero">
      <div class="hero">
        <div class="hero-text-box">
          <h1 class="heading-primary">
            A healthy meal delivered to your door, every single day
          </h1>
          <p class="hero-description">
            The smart 365-days-per-year food subscription that will make you eat
            healthy again. Tailored to your personal tastes and nutritional
            needs.
          </p>
          <a href="#" class="btn btn--full margin-right-small">Start eating well</a>
          <a href="#" class="btn btn--outline">Learn more &darr;</a>
          <div class="delivered-meals">
            <div class="delivered-imgs">
              <img src="./assets/img/customers/customer-1.jpg" alt="Customer Photo">
              <img src="./assets/img/customers/customer-2.jpg" alt="Customer Photo">
              <img src="./assets/img/customers/customer-3.jpg" alt="Customer Photo">
              <img src="./assets/img/customers/customer-4.jpg" alt="Customer Photo">
              <img src="./assets/img/customers/customer-5.jpg" alt="Customer Photo">
              <img src="./assets/img/customers/customer-6.jpg" alt="Customer Photo">
            </div>
            <p class="delivered-text"><span>250,000+</span> meals delivered last year!</p>
          </div>
        </div>
        <div class="hero-image-box">
          <img
            src="../src/assets/img/hero.png"
            class="hero-img"
            alt="Women enjoying food, meals in storage container and food bowls on table"
          />
        </div>
      </div>
    </section>
    <section class="section-how">
      <div class="container grid grid--2-cols">
        <div>Test 1</div>
        <div>Test 2</div>
        <div>Test 3</div>
        <div>Test 4</div>
      </div>
    </section>
  </div>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.section-how{
  padding: 9.6rem 0;
  background-color: orangered;
}
.container{
  max-width: 120rem;
  margin: 0 auto;
  padding: 0 3.2rem;
}
.grid{
  display: grid;
  gap: 9.6rem;
  
}
.grid--2-cols{
  grid-template-columns: repeat(2, 1fr);
}
.grid--3-cols{
  grid-template-columns: repeat(3, 1fr);
}
.grid--4-cols{
  grid-template-columns: repeat(4, 1fr);
}
.section-how div div{
  padding: 100px;
  font-size: 50px;
  background-color: #333;
}
</style>
