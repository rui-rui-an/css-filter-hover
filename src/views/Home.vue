<template>
  <div class="home">
    <div class="mybox">
      <div class="img_box">
        <img src="@/assets/icon-0-allsearch.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return{
    }
  },
  methods: {
  }
}
</script>

<style lang="less" scoped>
.home {
  .mybox {
    width: 200px;
    height: 200px;
    background-color: var(--bgc);
    cursor: pointer;
    border: 1px solid #000;
    display: flex;
    justify-content: center;
    align-items: center;
    .img_box{
      width: 50px;
      height: 50px;
      overflow: hidden;
      img{
         width: 50px;
         height: 50px;
      }
    }
  }
  .mybox:hover{
    border: 1px solid #d4b021;
  }
  .mybox:hover .img_box img{
    margin-left: -100px;
    filter: drop-shadow(50px 0 0 #d4b021);
  }
}
</style>