<template>
  <div id="app3">
    <span v-if="seen">hoge</span>
    <button @click="off">表示OFF</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      seen: true,
    };
  },
  methods: {
    off() {
      this.seen = false;
    },
  },
};
</script>
