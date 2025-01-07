<template>
  <div id="app9">
    <Template9
      v-for="item in itemList"
      :key="item.id"
      :prop1="item"
      prop2="です"
    />
  </div>
</template>

<script>
import Template9 from "./Template9.vue";

export default {
  data() {
    return {
      itemList: [
        { id: 0, text: "0番" },
        { id: 1, text: "1番" },
        { id: 2, text: "2番" },
      ],
    };
  },
  components: {
    Template9,
  },
};
</script>
