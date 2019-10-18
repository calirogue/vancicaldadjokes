<template>
  <div class="container">
    <AppHeader />
    <nuxt />
  </div>
</template>

<script>
import AppHeader from '../components/AppHeader';
export default {
  components: {
    AppHeader
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  background: #f2f2f2;
}

a {
  color: #333;
  text-decoration: none;
}

ul {
  list-style: none
}

.container {
  max-width: 800px;
  margin: 2rem auto;
  padding: 1rem 2rem;
  background: #ffffff;
}

</style>
