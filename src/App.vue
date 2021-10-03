<template>
  <div>
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
  </div>
</template>

<script>
export default {};
</script>

<style>
.section-hero{
background-color: #fdf2e9;
padding: 9.6rem 0 ;
}
.hero {
  max-width: 130rem;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 9.6rem;
}
.heading-primary{
  font-size: 5.2rem;
  font-weight: 700;
  line-height: 1.05;
  color: #333;
  letter-spacing: -0.5px;
  margin-bottom: 3.2rem;
}
.hero-description{
  font-size: 2rem;
  line-height: 1.5;
  margin-bottom: 4.8rem;
}
.btn:link, .btn:visited{
  display: inline-block;
  font-size: 2rem;
  font-weight: 600;
  text-decoration: none;
  padding: 1.6rem 3.2rem;
  border-radius: 9px ;
  transition: all 1s;
}
.btn--full:link, .btn--full:visited{
  background-color: #e67e22;
  color: #fff;
}
.btn--full:hover, .btn--full:active{
  background-color: #cf711f;
  color: #fff;
  
}
.btn--outline:link, .btn--outline:visited{
  background-color: #fff;
  color: #555;
}
.btn--outline:hover, .btn--outline:active{
  background-color: #fdf2e9;
  /* Trick to add border inside */
  box-shadow: inset 0 0 0 3px #fff;
}
.hero-img{
  width: 100%;
}
.margin-right-small{
  margin-right: 1.6rem !important;
}
.delivered-meals{
  display: flex;
  margin-top: 8rem;
  align-items: center;
  gap: 1.6rem;
}
.delivered-imgs{
  display: flex;
}
.delivered-imgs img{
  height: 4.8rem;
  width: 4.8rem;
  border-radius: 50%;
  margin-right: -1.6rem;
  border: 3px solid #fdf2e9;
}
.delivered-imgs img:last-child{
  margin: 0;
}
.delivered-text{
  font-size: 1.8rem;
  font-weight: 600;
}
.delivered-text span{
  color: #cf711f;
  font-weight: 700;
}
</style>
