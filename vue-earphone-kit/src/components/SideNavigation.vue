<template>
  <div class="side__navigation">
    <a href="#">Buttons</a>
    <a href="#">Typography</a>
    <a href="#">Colors</a>
    <a href="#">Input Fields</a>
    <a href="#">Nesto</a>
  </div>
</template>

<script>
export default {
  name: "SideNavigation"
};
</script>

<style lang="scss">
.side__navigation {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  height: 100%;
  width: 160px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: rgb(32, 32, 32);
  background-image: linear-gradient(
      45deg,
      black 25%,
      #343434 25%,
      #343434 75%,
      black 75%,
      black
    ),
    linear-gradient(
      45deg,
      black 25%,
      #343434 25%,
      #343434 75%,
      black 75%,
      black
    ),
    linear-gradient(to bottom, rgb(8, 8, 8), rgb(32, 32, 32));
  background-size: 3px 3px, 3px 3px, 3px 1px;
  background-position: 0px 0px, 5px 5px, 0px 0px;
  border-right: 2px solid #454545;
  overflow-x: hidden;
  padding-top: 20px;
}

.side__navigation a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-family: "mandan";
  letter-spacing: 3px;
  font-size: 40px;
  color: #818181;
  display: block;
}

.side__navigation a:hover {
  color: rgba(143, 255, 216, 0.7);
}
</style>
