<template>
  <div>
    <Navbar />
    <b-container>
      <Nuxt />
    </b-container>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';

export default {
    components: {
        Navbar
    }
};
</script>
