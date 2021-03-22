<template>
  <span>
    <header>
      <nav-bar cor="blue darken-2" logo="Social" url="#"/>
    </header>

    <main>
      <div class="container">
        <router-view /> 

      </div>
    </main>

    <footer-vue/>

  </span>
</template>

<script>
import NavBar from '@/components/layouts/NavBar'
import FooterVue from '@/components/layouts/FooterVue'
export default {
  name: "App",
  components: {
    NavBar,
    FooterVue
  }
};
</script>

<style>
</style>
