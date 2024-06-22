<template>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</template>

<script setup>

// Lógica opcional del componente, por ejemplo, manejo de eventos
</script>

<style scoped>
  /* Estilos específicos para el componente Navbar */
  nav {
      padding: 10px;
      background-color: #333;
  }

  ul {
      padding: 0;
      margin: 0;
      list-style-type: none;
  }

  li {
      display: inline;
      margin-inline-end: 10px;
  }

  a {
      color: white;
      padding-block: 5px;
      padding-inline: 10px;
      text-decoration: none;
  }
</style>
