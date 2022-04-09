<template >
  <img :src="avatar" :alt="description">
</template>
<script>
  export default {
    name: 'Picture',
    data() {
      return {
        avatar: '/img/gelado.webp',
        description: 'Gelado kkkk',
      };
    },
  };
</script>
<style >
</style>