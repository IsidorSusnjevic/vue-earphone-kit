<template>
  <div class="app">
    <SideNavigation />
    <EButton style="margin-top: 100px" />
    <EInputText style="margin-top: 100px" />
    <EInputRange style="margin-top: 100px" />
    <EInputChackbox style="margin-top: 100px" />
    <EInputRadio style="margin-top: 100px" />
    <EInputRadio style="margin-top: 10px" />
    <TypographySample style="margin-top: 10px" />
    <Icon />
  </div>
</template>

<script>
import EButton from "./components/EButton";
import EInputText from "./components/EInputText";
import EInputRange from "./components/EInputRange";
import EInputChackbox from "./components/EInputChackbox";
import EInputRadio from "./components/EInputRadio";
import TypographySample from "./components/TypographySample";
import Icon from "./components/Icon";
import SideNavigation from "./components/SideNavigation";

export default {
  name: "App",
  components: {
    EButton,
    EInputText,
    EInputRange,
    EInputChackbox,
    EInputRadio,
    TypographySample,
    Icon,
    SideNavigation
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
  /* CARBON FIBER */
  //  background-color: rgb(32, 32, 32);
  // background-image: linear-gradient(
  //     45deg,
  //     black 25%,
  //     #343434 25%,
  //     #343434 75%,
  //     black 75%,
  //     black
  //   ),
  //   linear-gradient(
  //     45deg,
  //     black 25%,
  //     #343434 25%,
  //     #343434 75%,
  //     black 75%,
  //     black
  //   ),
  //   linear-gradient(to bottom, rgb(8, 8, 8), rgb(32, 32, 32));
  // background-size: 3px 3px, 3px 3px, 3px 1px;
  // background-position: 0px 0px, 5px 5px, 0px 0px;
  // border-right: 2px solid #454545;
  // overflow-x: hidden;
  // padding-top: 20px;
  .app {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
