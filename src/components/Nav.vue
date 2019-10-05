<template>
  <nav class="nav">
    <a href="#" class="nav-logo">vue</a>
    <ul class="nav-list">
      <li class="nav-item">
        <a href="/contact">contact</a>
      </li>
      <li class="nav-item">
        <a href="/about">about</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.nav {
  background-color: #fff;
  box-shadow: 0 0 3px rgba(51, 51, 51, 0.3);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 40px;
  height: 60px;
  font-size: 18px;
  margin-bottom: 20px;
}

.nav .nav-logo {
  display: inline-block;
  font-weight: bold;
  font-size: 24px;
}

.nav-list {
  display: flex;
  width: 200px;
  justify-content: space-between;
}
</style>

