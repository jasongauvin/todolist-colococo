<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <todo-header></todo-header>
    <todo-table></todo-table>
  </div>
</template>

<script>
// @ is an alias to /src
import TodoTable from "@/components/TodoTable.vue";
import TodoHeader from "@/components/TodoHeader.vue";

export default {
  name: "Todo",
  components: {
    TodoTable,
    TodoHeader
  }
};
</script>
