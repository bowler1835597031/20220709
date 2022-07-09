<template>
  <div>
    <p>关注明星</p>
    <p>发现精彩</p>
    <p>寻找伙伴</p>
    <p>加入我们</p>
    <p>
      人名: --
      {{ $route.params.username }}=={{ $route.params.id }}
    </p>
    <!-- 第二种方法 -->
    <p>id:{{ $route.query.id }}---{{ $route.query.age }}</p>
    <!-- 第一种方法 -->
  </div>
</template>

<script>
export default {};
</script>

<style></style>
