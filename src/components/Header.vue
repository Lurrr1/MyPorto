<script>
export default {
  name: "Header",
};
</script>

<template>
  <header class="header">
    <a href="#" class="logo">Portfolio</a>
    <i class="fa-solid fa-bars" id="icon-menu"></i>
    <nav class="navbar">
      <a href="#home" class="active">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
</template>

<style scoped>
.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  padding: 2rem 9%;
  z-index: 100;
  background: #070f2b /*var(--bg-color)*/;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 2.5rem;
  color: var(--text-color);
  font-weight: 700;
  cursor: default;
}

.navbar a {
  font-size: 1.5rem;
  color: var(--text-color);
  margin-left: 4rem;
  font-weight: 700;
}

.navbar a:hover,
.navbar a.active {
  color: var(--text-color);
}

#icon-menu {
  font-size: 3.6rem;
  color: var(--text-color);
  display: none;
}
</style>
