<template>
  <div>
    <Header />
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
          <a href="#" class="btn btn--full margin-right-small"
            >Start eating well</a
          >
          <a href="#" class="btn btn--outline">Learn more &darr;</a>
          <div class="delivered-meals">
            <div class="delivered-imgs">
              <img
                src="./assets/img/customers/customer-1.jpg"
                alt="Customer Photo"
              />
              <img
                src="./assets/img/customers/customer-2.jpg"
                alt="Customer Photo"
              />
              <img
                src="./assets/img/customers/customer-3.jpg"
                alt="Customer Photo"
              />
              <img
                src="./assets/img/customers/customer-4.jpg"
                alt="Customer Photo"
              />
              <img
                src="./assets/img/customers/customer-5.jpg"
                alt="Customer Photo"
              />
              <img
                src="./assets/img/customers/customer-6.jpg"
                alt="Customer Photo"
              />
            </div>
            <p class="delivered-text">
              <span>250,000+</span> meals delivered last year!
            </p>
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
    <SectionFeatured />
    <SectionHow />
    <SectionMeal />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import SectionHow from "./components/SectionHow.vue";
import SectionFeatured from "./components/SectionFeatured.vue";
import SectionMeal from "./components/SectionMeal.vue";
export default {
  components: {
    Header,
    SectionHow,
    SectionFeatured,
    SectionMeal,
  },
  methods: {},
};
</script>

<style>
.section-hero {
  background-color: #fdf2e9;
  padding: 4.8rem 0 9.6rem 0;
}
.hero {
  max-width: 130rem;
  margin: 0 auto;
  padding: 0 3.2rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 9.6rem;
}
.heading-primary,
.heading-secondary {
  font-weight: 700;
  letter-spacing: -0.5px;
  color: #333;
  /* color: #45260a; */
}
.heading-primary {
  font-size: 5.2rem;
  line-height: 1.05;
  margin-bottom: 3.2rem;
}
.heading-secondary {
  font-size: 4.4rem;
  line-height: 1.2;
  margin-bottom: 9.6rem;
}
.heading-tertiary {
  font-size: 3rem;
  line-height: 1.2;
  margin-bottom: 3.2rem;
}
.subheading {
  display: block;
  font-size: 1.6rem;
  font-weight: 500;
  color: #cf711f;
  text-transform: uppercase;
  margin-bottom: 1.6rem;
  letter-spacing: 0.75px;
}
.hero-description {
  font-size: 2rem;
  line-height: 1.5;
  margin-bottom: 4.8rem;
}
.hero-img {
  width: 100%;
}
.delivered-meals {
  display: flex;
  margin-top: 8rem;
  align-items: center;
  gap: 1.6rem;
}
.delivered-imgs {
  display: flex;
}
.delivered-imgs img {
  height: 4.8rem;
  width: 4.8rem;
  border-radius: 50%;
  margin-right: -1.6rem;
  border: 3px solid #fdf2e9;
}
.delivered-imgs img:last-child {
  margin: 0;
}
.delivered-text {
  font-size: 1.8rem;
  font-weight: 600;
}
.delivered-text span {
  color: #cf711f;
  font-weight: 700;
}
.container {
  max-width: 120rem;
  margin: 0 auto;
  padding: 0 3.2rem;
}
.grid {
  display: grid;
  column-gap: 6.4rem;
  row-gap: 9.6rem;
}
.grid--2-cols {
  grid-template-columns: repeat(2, 1fr);
}
.grid--3-cols {
  grid-template-columns: repeat(3, 1fr);
}
.grid--4-cols {
  grid-template-columns: repeat(4, 1fr);
}
.grid-center-v {
  align-items: center;
}
</style>
