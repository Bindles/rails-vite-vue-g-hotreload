<template lang="">
  <div>
    <button @click="increment" id="counter-button">Increment</button>
    <p>Count is: {{ count }}</p>
  </div>
</template>
<script>
export default {
  data() {
    return { count: 0 };
  },
  methods: {
    increment() {
      this.count++;
    },
  },
};
</script>
<style lang="css">
#button {
    background-color: red;
}
}
</style>
