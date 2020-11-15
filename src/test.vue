<template>
  <div class="test">
    <!--html code-->
    <li
      v-for="(item) in [1,2,4]"
      :key="item"
      a="2"
      b="3">{{ item }}</li>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  name: 'Test',
  components: {},
  data() {
    return {}
  }
}
</script>

<style scoped lang="less">
.test {
  /* less */
  div {
    width: 200px;
    color: red;

    span {
      height: 19%;

      a {
        height: 20px;
        color: #fff;
      }
    }
  }
}

</style>
