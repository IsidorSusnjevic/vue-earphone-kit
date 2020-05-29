<template>
  <button class="button">Button</button>
</template>

<script>
export default {
  name: "EButton"
};
</script>

<style lang="scss">
.button {
  color: rgba(143, 255, 216, 0.75);
  height: 100px;
  width: 100px;
  border: none;
  outline: none;
  // border-radius: 36px;
  // background: transparent;
  // box-shadow: 8px 8px 19px rgba(0,0,0,0.4), -8px -8px 19px rgba(255,255,255,0.2);
  border-radius: 50px;
  background: #333333;
  box-shadow: 5px 5px 10px #2b2b2b, -5px -5px 10px #3b3b3b;
}
</style>