<template>
    <div class="uk uk-navbar">
        <ul>Главная</ul>
        <ul>Главная</ul>
        <ul>Главная</ul>
        <ul>Главная</ul>
        <ul>Главная</ul>
    </div>
</template>

<script>

export default {
  name: 'app',
  components: {
  }
}
</script>

<style lang="less">
  @import "~uikit/src/less/uikit.theme.less";
  div, uk-navbar {
      background-color: black;
      position:relative;
      float:left;
      margin:0 10px;
      height:40px;
  }
  body {
      overflow: auto;
      height: 100vh;
      background-color: black;
      background-image: url("assets/fon-warcraft1.jpg");
      background-position: center;
      background-size: cover;
  }


    </style>