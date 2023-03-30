<template>
	<test></test>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import {ref} from 'vue'
import cam from './views/cam.vue'
import test from './views/test.vue'
const tackPhoto = ref(false);

export default defineComponent({
  name: 'App',
  components: {
    //cam
	test
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
