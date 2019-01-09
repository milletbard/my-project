<template>
  <div class="container-fluid">
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
  height: 100vh;
  width: 100vw;
}

html,
ul {
  padding: 0px;
}

.status {
  float: right;
}
</style>
