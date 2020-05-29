<template>
  <label class="radio__container">
    <input type="radio" checked="checked" name="radio" />
    <span class="check"></span>
  </label>
</template>

<script>
export default {
  name: "EInputRadio"
};
</script>

<style lang="scss">
.radio__container {
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
.radio__container input {
  opacity: 0;
  cursor: pointer;
  height: 0;
  width: 0;
}
.check {
  position: absolute;
  top: 0;
  left: 0;
  height: 30px;
  width: 30px;
  border-radius: 48px;
  background: #333333;
  box-shadow: inset -7px 7px 14px #272727, inset 7px -7px 14px #3f3f3f;
}
.radio__container:hover input ~ .check {
  background-color: rgba(143, 255, 216, 1);
}
.radio__container input:checked ~ .check {
  border-radius: 48px;
  background: #333333;
  box-shadow: 5px 5px 10px #2b2b2b, -5px -5px 10px #3b3b3b;
}
.check:after {
  content: "";
  position: absolute;
  display: none;
}
.radio__container input:checked ~ .check:after {
  display: block;
border: solid rgba(143, 255, 216, 0.75);

}
.radio__container .check:after {
  top: 8px;
  left: 7.4px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
}
</style>