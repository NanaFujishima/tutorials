<template>
  <div id="app2">
    <p>{{ count }}回クリックしました</p>
    <button @click="increment">カウントを増やす</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count += 1;
    },
  },
};
</script>
