<template>
  <input type="range" />
</template>

<script>
export default {
  name: "EInputRange"
};
</script>

<style lang="scss">
input[type="range"] {
  -webkit-appearance: none;
  margin: 10px 0;
  width: 200px;
  background: transparent;
  // overflow: hidden; ----- test
}
input[type="range"]:focus {
  outline: none;
}
input[type="range"]::-webkit-slider-runnable-track {
  width: 100%;
  height: 10px;
  cursor: pointer;
  border-radius: 93px;
  background: #3d3d3d;
  box-shadow: inset 1px 1px 3px #2a2a2a, inset -2px -2px 3px #353535;
  border: 0.1px solid #2b2b2b;
}
input[type="range"]::-webkit-slider-thumb {
  height: 40px;
  width: 20px;
  border-radius: 93px;
  border: 1px solid #373737;
  background: linear-gradient(145deg, #373737, #2e2e2e);
  box-shadow: 2px 2px 3px #2b2b2b, -1px -1px 2px #3b3b3b;
  // box-shadow: -100px 0 0  100px rgba(143, 255, 216, 0.7); -----test
  cursor: ew-resize;
  -webkit-appearance: none;
  margin-top: -20px;
}
</style>