<template>
  <div>
    <h2>Search组件</h2>
    <h3>params.keyword: {{$route.params.keyword}}</h3>
    <h4>query.keyword2: {{$route.query.keyword2}}</h4>
    <h4>props.keyword3: {{keyword3}}</h4>
    <h4>props.keyword4: {{keyword4}}</h4>
  </div>
</template>

<script>
export default {
  name: 'Search',
  props: ['keyword3', 'keyword4']
}
</script>

<style lang="less" scoped>

</style>
