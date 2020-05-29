<template>
  <label class="checkbox__container">
    <input type="checkbox" checked="checked" />
    <span class="checkmark"></span>
  </label>
</template>

<script>
export default {
  name: "EInputChackbox"
};
</script>

<style lang="scss">
/* The container */
.checkbox__container {
  display: block;
  position: relative;
  padding-left: 35px;
  margin-bottom: 12px;
  cursor: pointer;
  font-size: 22px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.checkbox__container input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
  height: 0;
  width: 0;
}
.checkmark {
  position: absolute;
  top: 0;
  left: 0;
  height: 30px;
  width: 30px;
  border-radius: 0px;
  background: #333333;
  box-shadow: 5px 5px 10px #2b2b2b, -5px -5px 10px #3b3b3b;
  border: 1px solid #373737;
}
.checkbox__container:hover input ~ .checkmark {
  background-color: rgba(143, 255, 216, 0.5);
  box-shadow: inset -7px 7px 14px #272727, inset 7px -7px 14px #3f3f3f;
  border: 1px solid #373737;
}
.checkbox__container input:checked ~ .checkmark {
  border-radius: 0px;
  background: #333333;
  box-shadow: inset -7px 7px 14px #272727, inset 7px -7px 14px #3f3f3f;
  border: 1px solid #373737;
}
.checkmark:after {
  content: "";
  position: absolute;
  display: none;
}
.checkbox__container input:checked ~ .checkmark:after {
  display: block;
}
.checkbox__container .checkmark:after {
  left: 12px;
  top: 7px;
  width: 5px;
  height: 10px;
  border: solid rgba(143, 255, 216, 0.75);
  border-width: 0 3px 3px 0;
  -webkit-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  transform: rotate(45deg);
}
</style>