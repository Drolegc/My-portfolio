<template>
  <div class="about container mx-auto">
    <router-link to="/" class="btn btn-dark rounded">Home</router-link>
    <about-me :img-dog='img'></about-me>
  </div>
</template>

<script>

  import aboutMe from '@/components/aboutMe.vue';
  import { mapGetters } from 'vuex';


  export default {
    name: 'about',
    components: {
      aboutMe
    },
    computed: {
      ...mapGetters(['img']),
    }
  }

</script>

<style>
  .about {
    margin-top: 25vh;
  }

  .about .btn {
    margin-left: 50%;
  }
</style>