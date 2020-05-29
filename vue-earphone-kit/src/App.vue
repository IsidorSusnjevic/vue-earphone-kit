<template>
  <div class="app">
    <EButton style="margin-top: 100px" />
    <EInputText style="margin-top: 100px" />
    <EInputRange style="margin-top: 100px" />
    <EInputChackbox style="margin-top: 100px" />
    <EInputRadio style="margin-top: 100px" />
    <EInputRadio style="margin-top: 10px" />
    <TypographySample style="margin-top: 10px" />
  </div>
</template>

<script>
import EButton from "./components/EButton";
import EInputText from "./components/EInputText";
import EInputRange from "./components/EInputRange";
import EInputChackbox from "./components/EInputChackbox";
import EInputRadio from "./components/EInputRadio";
import TypographySample from "./components/TypographySample";


export default {
  name: "App",
  components: {
    EButton,
    EInputText,
    EInputRange,
    EInputChackbox,
    EInputRadio,
    TypographySample
  }
};
</script>

<style lang="scss">
@import url("assets/scss/main.scss");


* {
  margin: 0;
  padding: 0;
}
body {
  background-color: #323232;
  .app {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
