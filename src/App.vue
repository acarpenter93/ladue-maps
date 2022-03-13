<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="logo">
      <img alt="Ladue logo" src="@/assets/logo.png" />
    </div>
    <h1> Welcome to Ladue Horton Watkins High School</h1>
  </header>

  <RouterView />
</template>

<style>
@import '@/assets/base.css';

body {
  padding: 1rem; 
 }

#app {
  background: #F3F3F3; 
  margin: 0 auto;

  font-weight: normal;
}

header {
  align-items:center;
  background:#2C4AA0;
  display:flex;
  color:#FFF;
  height: 156px;
}
h1 {
  flex:1;
  text-align:center;
}
.logo {
  align-items:center;
  background:#243C82;
  display:flex;
  height:156px;
  justify-content: center;
  width:25%; 
}
</style>
