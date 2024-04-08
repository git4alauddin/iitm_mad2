<template>
    <nav class="navbar">
      <ul>
        <li><router-link to="/home">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style scoped>
 
  .navbar {
    background-color: #333;
    color: #fff;
  }
  
  .navbar ul {
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
  