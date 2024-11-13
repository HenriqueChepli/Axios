<script setup>
</script>
<template>
    <nav>
      <router-link to="/" class="nav-link">Home</router-link>
      <router-link to="/filmes" class="nav-link">Filmes</router-link>
      <router-link to="/tv" class="nav-link">Programas de TV</router-link>
    </nav>
</template>
<style scoped>
    nav {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 25px 0;
  background-color: #1f1f1f; 
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
}

.nav-link {
  color: #fff;
  text-decoration: none;
  font-size: 1.2rem;
  font-weight: bold;
  margin: 0 20px;
  border-bottom: 1px solid transparent;
  transition: border 0.3s ease, transform 0.3s ease;
}

.nav-link:hover { 
    border-bottom: 1px solid #fff;
  transform: scale(1.1) translateY(-5px); 
}

.nav-link:focus {
  outline: none;
  color: #e50914; 
}


@media (max-width: 768px) {
  .nav-link {
    font-size: 1rem;
    margin: 0 10px;
  }
}
</style>