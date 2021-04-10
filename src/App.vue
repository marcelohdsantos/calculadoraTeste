<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./main/Calculator";

export default {
  components: { Calculator },
};
</script>

<style>
@font-face {
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
  font-family: "RobotoMono", "Courier New", Courier, monospace;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  background: rgb(2, 0, 36);
  background: linear-gradient(
    90deg,
    rgba(2, 0, 36, 1) 5%,
    rgba(9, 121, 96, 0.9962185557816877) 59%,
    rgba(8, 128, 109, 1) 83%,
    rgba(0, 212, 255, 1) 99%
  );
}
</style>