<template>
  <div class="picture">
    <canvas></canvas>
  </div>
</template>

<script>
export default {
  name: "pictureVue"
}
</script>

<style lang="scss" scoped>
.picture {
  display: block;
  width: 100%;
  height: 100vh;
  padding: 25px;
  box-sizing: border-box;

  canvas {
    display: block;
    width: 70%;
    height: 80%;
    margin: 0 auto;
    box-shadow: 6px 6px 12px 0 transparentize($color: #171717, $amount: 0.5);
  }
}
</style>