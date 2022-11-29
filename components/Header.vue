<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow fixed-top">
    <div id="home" class="container">
      <a class="navbar-brand" href="#">
        <img src="@/assets/vntu-symbol2.jpeg" width="40" alt="vntu-symbol">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#proposition">Що пропонуємо?</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#features">Переваги</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact-us">Зворотній звʼязок</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contacts">Контакти</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>

</style>
