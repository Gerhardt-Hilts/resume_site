<template>
  <div class="home">
    <Jumbotron />
      <div style="height: 1000px;"></div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Jumbotron from '@/components/Jumbotron.vue';

export default {
  name: 'home',
  components: {
    Jumbotron
  }
}
</script>
