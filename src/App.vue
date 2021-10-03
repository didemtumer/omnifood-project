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
            needs. We have delivered 250,000+ meals last year!
          </p>
          <a href="#" class="btn">Start eating well</a>
          <a href="#" class="btn">Learn more &darr;</a>
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
  background-color: #e67e22;
  color: #fff;
  font-size: 2rem;
}
.hero-img{
  width: 100%;
}
</style>
