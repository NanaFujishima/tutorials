<template>
  <li>{{ prop1.id }}は{{ prop1.text }}{{ prop2 }}</li>
</template>

<script>
export default {
  props: ["prop1", "prop2"],
};
</script>
