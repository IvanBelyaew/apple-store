<template>
  <div class="main">
    <Header></Header>
    <Banner></Banner>
    <Banner2></Banner2>
    <RouterView></RouterView>
    <Categories></Categories>
    <Footer></Footer>
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Banner from './components/Banner.vue'
import Banner2 from './components/Banner.vue'
import { RouterView } from 'vue-router'
import Categories from './components/Categories.vue'
import Footer from './components/Footer.vue'
</script>

<style scoped>
.main {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex-wrap: wrap;
  overflow: scroll;
}
</style>
