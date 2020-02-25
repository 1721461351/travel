<template>
  <div class="header">
    <div class="header-left">左</div>
    <div class="header-input">中</div>
    <div class="header-right">右</div>
  </div>
</template>

<style lang="stylus" scoped>
.header {
  height: 0.83rem;
  background-color :#00bcd4
}
.header-left{
    width :0.64rem
    float :left
}
.head-input{
    border-radius : 0.1rem
    margin-top:.12rem
    margin-left .2rem
}
.header-right{
    width :1.12rem
    float :right
}
</style>

<script>
export default {
  name: "homeHeader"
};
</script>