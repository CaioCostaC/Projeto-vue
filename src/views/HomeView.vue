<template>
  <div>
    <Banner />
    <p>banner</p>
    <div class="main-container">
      <h1>Monte o seu burger:</h1>
      <p>Formulário</p>
    </div>
  </div>
</template>

<script>
  import Banner from "../components/Banner.vue";

  export default {
    name: 'HomeView',
    components: {
      Banner
    }
  }
</script>
