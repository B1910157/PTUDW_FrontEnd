<!-- <script>
export default{

}
</script>
npm run dev

<template>
  <h1>Hello, VueJS!!!</h1>
</template>

<style>
.page{
  max-width: 400px;
  margin: auto;

}
</style> -->

<script>
import AppHeader from "@/components/AppHeader.vue";
export default {
  components: {
    AppHeader,
  },

};
</script>
<template>
  <div id="app" >
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>
<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>