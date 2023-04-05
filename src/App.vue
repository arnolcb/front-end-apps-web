<template>
  <div>
    <Header /> <!-- Use the header component in your template -->
    <!-- Your app content goes here -->
  </div>
</template>

<script>
import Header from './components/Header.vue' // Import the header component

export default {
  components: {
    Header // Register the header component in your Vue instance
  },
  // Your app logic goes here
}
</script>

<style scoped>
/* Your app styles go here */
</style>
