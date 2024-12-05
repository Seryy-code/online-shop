<template>
  <div>
    <p>Count: {{ exampleStore.count }}</p>
    <button @click="exampleStore.increment">Increment</button>
  </div>
</template>

<script>
import { useExampleStore } from "@/stores/example";

export default {
  setup() {
    const exampleStore = useExampleStore();
    return { exampleStore };
  },
};
</script>
