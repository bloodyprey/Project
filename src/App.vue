<template>
    <div>
        <nav class="uk-navbar">
            <a class="uk-logo" href=""><img src="../public/Logo.png" height="150" width="150"/></a>
            <ul class="uk-navbar-nav">
                <li><a href="">Главная</a></li>
                <li><a href="">Игры</a></li>
                <li><a href="">Магазин</a></li>
                <li><a href="">Новости</a></li>
                <li><a href="">Реклама</a></li>
                <li><a href="">Поддержка</a></li>
            </ul>
        </nav>
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

  .uk-navbar {
      background: transparent;
      box-shadow: 3px 0 7px rgba(0,0,0,.3);
      padding: 20px;
  }
 body {
      overflow: auto;
      height: 100vh;
      background-color: black;
      background-image: url("assets/Mein-wow.jpg");
      background-position: center;
      background-size: cover;
  }


    </style>