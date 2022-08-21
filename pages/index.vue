<template>
  <NuxtLayout name="custom">
    <div class="app">
      <div class="container">
        <div class="hero-content">
          <h1>Welcome to RestaurantLy</h1>
          <h3>Top 50 Restaurants Across The World</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad
            provident, distinctio eum id deserunt deleniti nobis sunt alias,
            illum rem aperiam cupiditate, magnam earum vel error veniam quos
            facilis dolore!
          </p>
          <a class="btn-hero" href="/restaurant">Restaurants</a>
        </div>
      </div>
    </div>
  </NuxtLayout>
</template>

<script setup lang="ts"></script>

<style scoped>
.app {
  background-image: linear-gradient(
      45deg,
      rgba(61, 61, 61, 0.9),
      rgba(49, 8, 8, 0.9)
    ),
    url("./assets/hero-bg.jpg");
  min-height: 100vh;
  background-size: cover;
  padding: 1px;
}
.hero-content {
  position: relative;
  display: grid;
  place-content: center;
  min-height: calc(100vh - 2rem);
  max-width: 800px;
  margin: 2rem auto 0;
  color: #fff;
  text-align: center;
  display: grid;
  gap: 1rem;
}
h1 {
  font-size: 10vmin;
  line-height: 1;
  color: #e49d1b;
  letter-spacing: 2px;
}
h3 {
  font-weight: 400;
  font-size: 2rem;
}
p {
  font-size: 1.3rem;
  font-weight: 300;
  color: #eee;
}
.btn-hero {
  padding: 0.8rem 3rem;
  background: #e49d1b;
  width: max-content;
  border-radius: 100px;
  justify-self: center;
  font-size: 2rem;
  color: #fff;
  text-decoration: none;
  color: #eee;
  text-shadow: 2px 2px 10px rgba(37, 37, 37, 0.5);
}
</style>
