<template>
  <div class="app-nav">
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-dark navigation-bar">
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
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.app-nav {
  background: #212529;
}
.ml-auto {
  margin-left: auto;
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
  color: rgb(216, 216, 216);
  font-size: 1rem;
  font-weight: 400;
}
</style>
