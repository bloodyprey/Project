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
        <div class="uk-position-relative uk-visible-toggle uk-light" uk-slideshow>

            <ul class="uk-slideshow-items">
                <li>
                    <img src="assets/slide2" alt="" uk-cover>
                </li>
                <li>
                    <img src="assets/slide1.jpg" alt="" uk-cover>
                </li>
                <li>
                    <img src="images/light.jpg" alt="" uk-cover>
                </li>
            </ul>

            <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slideshow-item="previous"></a>
            <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slideshow-item="next"></a>

        </div>
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

  .uk-navbar-nav {
      margin-left: 150px;
  }
  .uk-logo {

          position: absolute;
          top: 15px;
          left: 50px;
          height: 54px;
          width: 84px;
  }
  .uk-navbar {
      background: transparent;
      box-shadow: 3px 0 7px rgba(0,0,0,.3);
      padding: 20px;
      height: 80px;
  }
  .uk-slideshow {
      height:300px;
      margin:50px auto;
      overflow:hidden;
      position:relative;

  }

 body {
      overflow: auto;
      height: 100vh;
      background-color: black;
      background-image: url("assets/Mein-wow.jpg");
      background-position: center;
      background-size: cover;
      background-repeat: repeat-y
  }


    </style>