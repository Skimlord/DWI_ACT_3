<script setup></script>

<template>
  <main>
    <nav class="navbar">
      <div>
        <img
          src="../assets/muerte_logo.png"
          alt="muerte logo"
          style="width: 30px"
        />
      </div>
      <div class="navbar-item-container">
        <div class="navbar-item">Menu item</div>
        <div class="navbar-item">Menu item</div>
        <div class="navbar-item">Menu item</div>
        <div class="navbar-item">Menu item</div>
      </div>
    </nav>
    <RouterView />
  </main>
</template>

<style scoped>
.navbar {
  color: green;
  height: 20px;
  background-color: black;
  display: flex;
  flex-flow: row;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
}

.navbar-item-container {
  width: 600px;
  display: flex;
  flex-flow: row;
  justify-content: space-around;
}

.navbar-item {
  cursor: pointer;
}
</style>
