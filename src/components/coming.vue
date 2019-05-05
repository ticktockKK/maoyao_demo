<template>
  <div class="coming">
    <h3>即将上映的电影</h3>
    <button @click="$router.push({name:'movieDetail'})">点击进入电影详情页</button>
  </div>
</template>
   
<script>
// 导出组件
export default {
  name: 'coming'
}
</script>

<style scoped>
</style>
