<template>
  <div>
    <!--使用组件标签-->
    <vuedemo/>
  </div>
</template>

<script>
// 引入组件
import vuedemo from './components/vuedemo.vue'
// 映射组件标签
export default{
  components: {
    vuedemo
  }
}
</script>

<style>

</style>
