<template>
  <div id="app">
    <Nav />
    <CardList myData="Cars are awesome!" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Nav from "./components/Nav";
import CardList from "./components/CardList.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
    Nav,
    CardList
  }
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

ul,
li {
  list-style: none;
}

a {
  text-decoration: none;
  color: #333;
}
</style>
