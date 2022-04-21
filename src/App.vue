<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Main from "@/components/Main.vue";
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: { MenuLateral, Main, Header, Footer }, 

};
</script>
<template>
  <MenuLateral />
  <Header />
  <Main />
  <Footer />
  <header id="header"></header>
  <main id="content"></main>
  <footer id="footer"></footer>
</template>
<style></style>
