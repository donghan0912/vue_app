<template>
  <img alt="Vue logo" src="./assets/logo.png">
<!--  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <TestComponent1 name="张三" gender="男" age="18"/>
  <TestComponent2/>
</template>

<!--免注册-->
<!--<script setup>
  import TestComponent1 from "./components/TestComponent1.vue";
  import TestComponent2 from "@/components/TestComponent2.vue";
</script>-->

<!--显示注册-->
<script>
// import HelloWorld from './components/HelloWorld.vue'
import TestComponent1 from "./components/TestComponent1.vue";
import TestComponent2 from "@/components/TestComponent2.vue";
export default {
  components: {
    // HelloWorld,
    TestComponent1,
    TestComponent2,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
