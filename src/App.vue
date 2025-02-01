<template>
  <div class="app-container" id="app">
    <TodoList />
  </div>
</template>

<script>
import TodoList from '@/components/blocks/TodoList.vue'

export default {
  name: 'App',
  components: {
    TodoList
  }
}
</script>

<style lang="scss">
.app-container {
  display: flex;
  justify-content: center;
  align-items: start;
  height: 100vh; /* Занять всю высоту экрана */
  background-color: #f4f4f9; /* Светлый фон */
}
</style>
