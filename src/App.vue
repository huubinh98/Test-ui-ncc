<script setup></script>

<template>
  <div class="home-page">
    <nav class="nav-bar">
      <ul>
        <li>Home</li>
        <li>Sevices</li>
        <li>News</li>
        <li>Blog</li>
        <li>Contact</li>
      </ul>
    </nav>
    <main class="main">
      <h1>
        <img src="./assets/image/logoNCC 1.png" alt="logo" />
      </h1>
      <div class="desc-title">
        <h3>Lorem ipsum dolor sit asmet?</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed tristique
          consequat placerat. Vestibulum auctor pellentesque sem, eu posuere
          erat hendrerit quis. Maecenas vel consequat turpis. Nam facilisis,
          ligula in mattis sodales, augue justo tristique nulla, sed lacinia
          ante eros ut mi. Morbi vitae diam augue. Aliquam vel mauris a nibh
          auctor commodo. Praesent et nisi eu justo eleifend convallis. Quisque
          suscipit maximus vestibulum. Phasellus congue mollis orci, sit amet
          luctus augue tristique eu. Donec vulputate odio neque, sed semper
          turpis pellentesque a.
        </p>
      </div>
      <div>
        <ItemLorems />
      </div>
    </main>
  </div>
</template>

<script setup>
import ItemLorems from "~/";
</script>

<style scoped>
.home-page {
  display: flex;
}
.main {
  width: 100%;
  max-width: 1510px;
  height: 100%;
  background-color: aqua;
}

.desc-title {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  background-color: #efefef;
  padding-top: 38px;
  padding-bottom: 38px;
}

.desc-title h3 {
  font-weight: 700;
  font-size: 18px;
  margin-bottom: 18px;
}

.desc-title p {
  font-size: 16px;
  max-width: 972px;
  width: 100%;
  text-align: center;
}

.nav-bar {
  max-width: 150px;
  width: 100%;
  height: 100vh;
  background-color: #191718;
  color: #ffffff;
}

.nav-bar ul {
  overflow: hidden;
}
.nav-bar ul li {
  border-bottom: 1px solid #5c5c5c;
  width: 100%;
  /* height: 44px; */
  color: #aaaaaa;
  padding-left: 16px;
  padding-top: 14px;
  padding-bottom: 11px;
  cursor: pointer;
}

.nav-bar ul li:hover {
  color: #ffffff;
}
</style>
