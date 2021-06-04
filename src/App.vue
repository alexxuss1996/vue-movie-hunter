<template>
  <div id="app">
    <hello-world></hello-world>
  </div>
  
</template>

<script setup>
import HelloWorld from './components/HelloWorld';
export default  {
  
  components: HelloWorld,
};


// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
}
</style>
