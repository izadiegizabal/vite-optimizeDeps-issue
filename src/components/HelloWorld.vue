<template>
  <VueCal />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import VueCal from 'vue-cal';
import 'vue-cal/dist/vuecal.css';

export default defineComponent({
  name: 'HelloWorld',
  components: {
    VueCal,
  },
});
</script>
