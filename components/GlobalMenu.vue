<template lang="pug">
.global--menu--wrap
  ul
    li
      a(href="#") メニュー1
    li
      a(href="#") メニュー2
    li
      a(href="#") メニュー3
    li
      a(href="#") メニュー4
</template>

<style lang="scss">
  .global--menu--wrap {
    position:fixed;
    left:0;
    top:0;
    min-height:100vh;
    max-height:100vh;
    ul {
      display:flex;
      flex-wrap:wrap;
      justify-content: space-between;
      li {
        width:20%;
      }
    }
  }
</style>