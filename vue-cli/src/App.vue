<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <!-- kebab : hello-world, Pascal : HelloWorld  -->
    <!-- 
      컴포넌트 명명법
      1<hello-world></hello-world>  -- 이걸써야 vscode drill down 가능
      2.<HelloWorld></HelloWorld>
      3.<HelloWorld/>> 
    -->
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  // 인스턴스 옵션 속성 or 컴포넌트 옵션 속성을 넣어 준다.
  name: "App",
  components: {
    HelloWorld
    // 'hello-world' : HelloWorld,
  }
};
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
