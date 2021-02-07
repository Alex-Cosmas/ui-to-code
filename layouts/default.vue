<template>
  <div class="container mx-auto px-10 bg-gray-50">
    <Nav />
    <Nuxt />
  </div>
</template>

<script>
import Nav from "~/components/nav/main";
export default {
  components: {
    Nav
  }
};
</script>
