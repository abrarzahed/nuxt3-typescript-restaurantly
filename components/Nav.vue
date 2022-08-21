<template>
  <nav class="navbar navbar-expand-lg navigation-bar">
    <a class="navbar-brand" href="/">RestaurantLy</a>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/restaurant">Restaurants</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script setup></script>

<style scoped>
.ml-auto {
  margin-left: auto;
}
.navigation-bar {
  position: absolute;
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
  left: 0;
  top: 0;
  width: 100%;
  padding-inline: 2rem;
  height: 4.6rem;
}
.navbar-brand {
  color: #eee;
  font-size: 2.2rem;
  font-weight: 900;
  letter-spacing: 5px;
  text-shadow: 5px 5px 5px rgba(37, 37, 37, 0.8);
  margin-top: -5px;
}
.nav-link {
  text-shadow: 2px 2px 10px rgba(37, 37, 37, 0.5);
  color: rgb(216, 216, 216) !important;
  font-size: 1rem;
  font-weight: 400;
}
</style>
