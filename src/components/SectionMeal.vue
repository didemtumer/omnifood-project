<template>
  <section class="section-meals">
    <div class="container center-text">
      <span class="subheading">Meals</span>
      <h2 class="heading-secondary">
        Omnifood AI chooses from 5,000+ recipes
      </h2>
    </div>

    <div class="container grid grid--3-cols margin-bottom-md">
      <div class="meal">
        <img
          src="../assets/img/meals/meal-1.jpg"
          class="meal-img"
          alt="Japanese Gyozas"
        />
        <div class="meal-content">
          <div class="meal-tags">
            <span class="tag tag--vegetarian">Vegetarian</span>
          </div>
          <p class="meal-title">Japanese Gyozas</p>
          <ul class="meal-attributes">
            <li class="meal-attribute">
              <ion-icon class="meal-icon" name="flame-outline"></ion-icon>
              <span><strong>650</strong> calories</span>
            </li>
            <li class="meal-attribute">
              <ion-icon class="meal-icon" name="restaurant-outline"></ion-icon>
              <span>NutriScore &reg; <strong>74</strong></span>
            </li>
            <li class="meal-attribute">
              <ion-icon class="meal-icon" name="star-outline"></ion-icon>
              <span><strong>4.9</strong> rating (537)</span>
            </li>
          </ul>
        </div>
      </div>

      <div class="meal">
        <img
          src="../assets/img/meals/meal-2.jpg"
          class="meal-img"
          alt="Avocado Salad"
        />
        <div class="meal-content">
          <div class="meal-tags">
            <span class="tag tag--vegan">Vegan</span>
            <span class="tag tag--paleo">Paleo</span>
          </div>
          <p class="meal-title">Avocado Salad</p>
          <ul class="meal-attributes">
            <li class="meal-attribute">
              <ion-icon class="meal-icon" name="flame-outline"></ion-icon>
              <span><strong>400</strong> calories</span>
            </li>
            <li class="meal-attribute">
              <ion-icon class="meal-icon" name="restaurant-outline"></ion-icon>
              <span>NutriScore &reg; <strong>92</strong></span>
            </li>
            <li class="meal-attribute">
              <ion-icon class="meal-icon" name="star-outline"></ion-icon>
              <span><strong>4.8</strong> rating (441)</span>
            </li>
          </ul>
        </div>
      </div>

      <div class="diets">
        <h3 class="heading-tertiary">Works with any diet:</h3>
        <ul class="list">
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Vegetarian</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Vegan</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Pescatarian</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Gluten-free</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Lactose-free</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Keto</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Paleo</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Low FODMAP</span>
          </li>
          <li class="list-item">
            <ion-icon class="list-icon" name="checkmark-outline"></ion-icon>
            <span>Kid-friendly</span>
          </li>
        </ul>
      </div>
    </div>

    <div class="container all-recipes">
      <a href="#" class="link">See all recipes &rarr;</a>
    </div>
  </section>
</template>
<style>
.section-meals {
  padding: 9.6rem 0;
}

.meal {
  box-shadow: 0 2.4rem 4.8rem rgba(0, 0, 0, 0.075);
  border-radius: 11px;
  overflow: hidden;
  transition: all 0.4s;
}

.meal:hover {
  transform: translateY(-1.2rem);
  box-shadow: 0 3.2rem 6.4rem rgba(0, 0, 0, 0.06);
}

.meal-content {
  padding: 3.2rem 4.8rem 4.8rem 4.8rem;
}

.meal-tags {
  margin-bottom: 1.2rem;
  display: flex;
  gap: 0.4rem;
}

.tag {
  display: inline-block;
  padding: 0.4rem 0.8rem;
  font-size: 1.2rem;
  text-transform: uppercase;
  color: #333;
  border-radius: 100px;
  font-weight: 600;
}

.tag--vegetarian {
  background-color: #51cf66;
}
.tag--vegan {
  background-color: #94d82d;
}
.tag--paleo {
  background-color: #ffd43b;
}

.meal-title {
  font-size: 2.4rem;
  color: #333;
  font-weight: 600;
  margin-bottom: 3.2rem;
}

.meal-attributes {
  list-style: none;
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.meal-attribute {
  font-size: 1.8rem;
  display: flex;
  align-items: center;
  gap: 1.6rem;
}

.meal-icon {
  height: 2.4rem;
  width: 2.4rem;
  color: #e67e22;
}

.meal-img {
  width: 100%;
}

.all-recipes {
  text-align: center;
  font-size: 1.8rem;
}
</style>
