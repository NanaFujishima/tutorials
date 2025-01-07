<template>
  <div id="app6">
    <ul>
      <li v-for="todo in todos" :key="todo.text">{{ todo.text }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      todos: [{ text: "PHP" }, { text: "Ruby" }, { text: "Python" }],
    };
  },
};
</script>
