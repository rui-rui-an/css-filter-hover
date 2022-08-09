<template>
  <div class="about">
    <img src="@/assets/logo.png" alt="" />
  </div>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
.about {
  img {
    -webkit-filter: grayscale(1); /* Webkit */
    filter: gray; /* IE6-9 */
    filter: grayscale(1); /* W3C */
  }
}
</style>