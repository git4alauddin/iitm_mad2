<template>
    <footer class="foot">
      <ul>
        <li><router-link to="/contact">Contact</router-link></li>
      </ul>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'foot'
  }
  </script>
  
  <style scoped>
  .foot {
    background-color: #333;
    color: #fff;
  }
  
  .foot ul {
    list-style-type: none;
    padding: 0;
  }
  
  .navbar ul li {
    display: inline-block;
    margin-right: 10px;
  }
  
  .navbar ul li a {
    color: #fff;
    text-decoration: none;
    padding: 5px 10px;
  }
  
  .navbar ul li a:hover {
    background-color: #555;
  }
  </style>
  