<template>
  <div id="app5">
    <p :class="class5">hogehoge</p>
    <p :class="class5">hogehoge2</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      class5: "blue",
    };
  },
};
</script>
