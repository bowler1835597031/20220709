<template>
  <div>
    <div class="nav_main">
      <router-link to="/find/recommend/a">新歌推荐</router-link>
      <router-link to="/find/recommend/b">新碟上架</router-link>
    </div>

    <div style="1px solid red;">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
