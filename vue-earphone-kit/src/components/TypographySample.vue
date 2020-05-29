<template>
  <div class="typo__container">
    <div class="typo__dual">
      <h1>A</h1>
      <p>a</p>
    </div>
    <div class="typo__mandan">
      <h1>A</h1>
      <p>a</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "TypographySample"
};
</script>

<style lang="scss">
.typo__container {
  display: flex;
  flex-direction: row;
  width: 600px;
  height: 200px;
  justify-content: center;
  align-items: center;
  //   background: red;
  .typo__dual {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 200px;
    width: 200px;
    background: black;
    border-radius: 61px;
    background: #333333;
    box-shadow: 6px 6px 12px #262626, -6px -6px 12px #404040;
    margin: 15px;
    h1 {
      text-align: center;
      color: rgba(143, 255, 216, 0.7);
      font-family: "Dual";
      font-weight: 700;
      font-size: 100px;
      letter-spacing: 10px;
    }
    p {
      text-align: center;
      color: rgba(143, 255, 216, 0.7);
      font-family: "Dual";
      font-weight: 700;
      font-size: 50px;
    }
  }
  .typo__mandan {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 200px;
    width: 200px;
    background: black;
    border-radius: 61px;
    background: #333333;
    box-shadow: 6px 6px 12px #262626, -6px -6px 12px #404040;
    margin: 15px;
    h1 {
      text-align: center;
      color: rgba(143, 255, 216, 0.7);
      font-family: "Mandan";
      font-weight: 700;
      font-size: 100px;
      letter-spacing: 10px;
    }
    p {
      text-align: center;
      color: rgba(143, 255, 216, 0.7);
      font-family: "Mandan";
      font-weight: 700;
      font-size: 50px;
    }
  }
}
</style>