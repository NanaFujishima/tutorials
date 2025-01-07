<template>
  <div id="app8">
    <ul>
      <Template8 prop8="次へ" />
      <Template8 :prop8="varString" />
    </ul>
  </div>
</template>

<script>
import Template8 from "./Template8.vue";

export default {
  data() {
    return {
      varString: "Hello!",
    };
  },
  components: {
    Template8,
  },
};
</script>
