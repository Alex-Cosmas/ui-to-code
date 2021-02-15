<template>
  <div class="bg-gray-50">
    <Nav />
    <div class="container mx-auto">
      <Nuxt />
    </div>
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
