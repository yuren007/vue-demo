<template>
  <div id="first">
    <h1>我是第一个组件</h1>
    <p>我想输出数据：<span class="msg">{{msg}}</span></p>
  </div>
</template>

<script>
    export default{
      name: 'first',
      data () {
        return {
          msg: '我说动态数据'
        }
      }
    }
</script>

<style>
  .msg {
    color : yellow;
  }
</style>
