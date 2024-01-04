<script lang="ts">
import { ref } from 'vue';
import { defineComponent } from '@nuxtjs/composition-api';

export default defineComponent({
  setup() {
    const title = ref('Hello nuxt 2.7 ts');
    return { title };
  },
});
</script>

<template>
  <div class="container">
    {{ title }}
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
