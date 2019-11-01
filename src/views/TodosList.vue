<template>
  <section>
    <ul>
      <li v-for="todo of todos" :key="todo.id">{{todo.text}}</li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      todos: [
        { id: "1", text: "List 1" },
        { id: "2", text: "List 2" },
        { id: "3", text: "List 3" },
        { id: "4", text: "List 4" },
        { id: "5", text: "List 5" }
      ]
    };
  }
};
</script>

