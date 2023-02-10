<!-- App.vue -->
<template>
    <div>
      <Navbar />
      <Header />
      <Main />
      <Footer />
    </div>
  </template>
  
  <script>
  import Navbar from './Navbar.vue'
  import Header from './Header.vue'
  import Main from './Main.vue'
  import Footer from './Footer.vue'
  
  export default {
    name: 'App',
    components: {
      Navbar,
      Header,
      Main,
      Footer
    }
  }
  </script>
  
  <style>
  body {
    background-color: #333;
    color: #fff;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  </style>
  