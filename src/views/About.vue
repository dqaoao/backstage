<template>
  <div class="not-found">
    <h1>啊哦！找不到相关页面o(╥﹏╥)o。</h1>
    <router-link to>
      <p @click="$router.back(-1)">返回上一级页面</p>
    </router-link>
  </div>
</template>

<script>
export default {
  // 项目主文件名称
  props: [],
  components: {},
  data() {
    return {};
  },
  //方法 函数写这里
  methods: {},
  //计算属性
  computed: {},
  //侦听器
  watch: {},
  //过滤器
  filters: {},
  //以下是生命周期
  //组件创建之前
  beforeCreate() {},
  //组件创建之后
  created() {},
  //页面渲染之前
  beforeMount() {},
  //页面渲染之后
  mounted() {},
  //页面视图数据更新之前
  beforeUpdate() {},
  //页面视图数据更新之后
  updated() {},
  //页面销毁之前
  beforeDestroy() {},
  //页面销毁之后
  destroyed() {},
};
</script>

<style lang="scss" scoped>
.not-found {
  width: 100%;
  height: 100vh;
  background-color: #6495ed;
  display: flex;
  justify-content: center;
  align-items: center;
  h1 {
    margin: 0;
    color: #fff;
  }
  a {
    color: #e0ffff;
    font-size: 14px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS',
      sans-serif;
    transform: translateY(10px);
  }
}
</style>
