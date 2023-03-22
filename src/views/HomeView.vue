<template>
  <div class="container"> 
    <Navbar/>
    <Posts/>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Posts from '@/components/Posts.vue';
export default {
  name: 'HomeView',
  components: {
    Navbar,
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
