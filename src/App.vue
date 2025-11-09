<template>
  <div class="container">
    <Header />
    <button>Add Task</button>
  </div>
</template>

<script>
import Header from "./Header.vue";
export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style>
#app {
  text-align: center;
  color: yellowgreen;
  margin-top: 60px;
}

.container {
  border: 1px solid steelblue;
  padding: 30px;
  max-width: 500px;
  margin: auto;
}

button {
  padding: 10px 20px;
  font-size: 15px;
  background: seagreen;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
</style>
