<template>
  <div>
    <div class="p-8">
      <h1 class="text-xl font-bold">Logo</h1>
    </div>
    <random-component></random-component>
  </div>
</template>

<script>
import RandomComponent from '../components/RandomComponent.vue';
export default {
  components: { RandomComponent },
  name: "Home",
};
</script>
