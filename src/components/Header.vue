<template>
  <div>{{ title }}</div>
</template>
<script>
import { defineComponent } from 'vue';

export default defineComponent({
  props: ['title'],
});
</script>
