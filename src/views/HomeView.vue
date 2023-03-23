<template>
  <div class="container"> 
    <Posts/>
  </div>
</template>

<script>
import Posts from '@/components/Posts.vue';
export default {
  name: 'HomeView',
  components: {
    Posts
  }
  };
</script>
<style>
  .container {
    max-width: 600px;
    margin: 0 auto;
  }

</style>
