<template>
  <div id="app" class="container">
    <english/>
  </div>
</template>

<script>
import english from "./components/english.vue";

export default {
  name: "app",
  components: {
    english
  }
};
</script>

<style>
@import url("http://fonts.googleapis.com/css?family=Montserrat:400,700");

body {
  background-color: #222;
  color: white;
  font-family: "Montserrat", sans-serif;
  display: grid;
  justify-items: center;
  align-items: center;
}
body,
html {
  margin: 0;
  height: 100%;
}
#app {
  width: 50%;
}

html,
ul {
  list-style: none;
  padding: 0px;
}

.row {
  width: 80%;
  margin: 0;
}
.status {
  float: right;
}
</style>
