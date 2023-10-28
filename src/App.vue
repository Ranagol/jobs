<template>
  <div class="app">
    Hello
  </div>
</template>

<!-- This below is different here, than with JS. It has lang="ts".-->
<script lang="ts">
import { defineComponent } from 'vue';

/**
 * This below is a slightly different way of creating Vue component objects than in JS
 */
export default defineComponent({
  name: 'App',
  components: {

  }
});
</script>

<style>

</style>
