
<template>
    <nav class="navbar">
      <div class="navbar-container">
        <div class="navbar-brand">
           Vue js
        </div>
        <div class="navbar-links">
          <router-link to="#contenido" class="navbar-link">¿Que es Vue js?</router-link>
          <router-link to="#porqueVue" class="navbar-link">¿Por qué Vue?</router-link>
          <router-link to="#sobreMi" class="navbar-link">Sobre mí</router-link>
        
        </div>
        <div class="navbar-toggle" @click="toggleMenu">
          <span class="navbar-toggle-icon"></span>
          <span class="navbar-toggle-icon"></span>
          <span class="navbar-toggle-icon"></span>
        </div>
      </div>
      <div v-if="isMenuOpen" class="navbar-mobile-links">
      
        <router-link to="#" class="navbar-link">¿Que es Vue js?</router-link>
          <router-link to="/about" class="navbar-link">¿Por qué Vue?</router-link>
          <router-link to="/services" class="navbar-link">Sobre mí</router-link>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name:"miBarra",
    data() {
      return {
        isMenuOpen: false,
      };
    },
    methods: {
      toggleMenu() {
        this.isMenuOpen = !this.isMenuOpen;
      },
    },
  };
  </script>
  
  <style scoped>
  .navbar {
    background-color:#00204a;
    color: white;
    padding: 2rem;


    
  }
  
  .navbar-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .navbar-brand {
    font-size: 1.5rem;
    font-weight: bold;
  }
  
  .navbar-links {
    display: flex;
    gap: 1rem;
  }
  
  .navbar-link {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
    transition: background-color 0.3s;
  }
  
  .navbar-link:hover {
    background-color: #555;
  }
  
  
  .navbar-toggle {
    display: none;
    flex-direction: column;
    cursor: pointer;
  }

  
  
  
  </style>
  