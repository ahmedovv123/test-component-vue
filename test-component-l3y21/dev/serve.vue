<script>
import { defineComponent } from 'vue';
import TestComponentL3y21 from '@/test-component-l3y21.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    TestComponentL3y21
  }
});
</script>

<template>
  <div id="app">
    <test-component-l3y21 />
  </div>
</template>
