<template>
  <div id="app">
    <Header></Header>
    <Intro></Intro>
    <Services></Services>
    <Quote></Quote>
    <Testimonial></Testimonial>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Intro from "./components/Intro.vue";
import Services from "./components/Services.vue";
import Quote from "./components/Quote.vue";
import Testimonial from "./components/Testimonial.vue";

export default {
  name: "app",
  components: {
    Header,
    Intro,
    Services,
    Quote,
    Testimonial
  }
};
</script>

<style>
</style>
