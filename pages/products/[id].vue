<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam eius, porro
      nobis eum voluptatem harum doloribus quod exercitationem? Nam, ducimus.
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style  scoped>
</style>