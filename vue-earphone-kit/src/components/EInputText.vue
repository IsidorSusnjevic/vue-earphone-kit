<template>
  <input class="input_text" type="text" name placeholder="type something" required />
</template>

<script>
export default {
  name: "EInputText"
};
</script>

<style lang="scss">
.input_text {
  width: 200px;
  height: 20px;
  background: transparent;
  border-radius: 36px;
  outline: none;
  box-shadow: inset 34px 34px 67px rgba(0, 0, 0, 0.45),
    inset -34px -34px 67px rgba(255, 255, 255, 0.2);
  padding: 10px;
  border: 0.2px solid #3d3d3d;
  color: rgba(143, 255, 216, 0.75);
  text-align: center;
  font-family: "Dual";
  font-size: 22px;
    ::placeholder {
    color: rgba(107, 107, 107, 1);
  }
}

</style>