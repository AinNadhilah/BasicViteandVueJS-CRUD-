<template>
  <img alt="Vue logo" class="logo" src="./assets/logo.png" />
  <HelloWorld msg="To do List using  Vue 3 + Vite" />
  <Todolist/>
  
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Todolist from './components/Todolist.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/master/active-rfcs/0040-script-setup.md
</script>

<style>
 * {
   box-sizing: border-box;
 }

 .container{
   max-width: 600px;
   margin: 0 auto;
 }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
 .logo{
   display: block;
   margin:20px auto;
   height:75px;
 }
</style>
