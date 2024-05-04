<!-- Sidebar.vue -->
<template>
    <aside>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Estudiantes</a></li>
        <li><a href="#">Asignaturas</a></li>
        <li><a href="#">Calificaciones</a></li>
        <li><a href="#">Contactos</a></li>
        <li><router-link to="/conocenos">Conócenos</router-link></li>
      </ul>
    </aside>
  </template>
  
  <script>
  export default {
    name: 'appSidebar'
  }
  </script>
  
  <style scoped>
  aside {
    width: 200px;
    background-color: #f4f4f4;
    padding: 20px;
  }
  
  ul {
    list-style: none;
    padding: 0;
  }
  
  li {
    margin-bottom: 10px;
  }
  
  a {
    text-decoration: none;
    color: #333;
  }
  
  a:hover {
    color: #555;
  }
  </style>
  