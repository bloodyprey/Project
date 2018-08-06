<template>
    <div>
        <nav class="uk-navbar">
            <a class="uk-logo" href=""><img src="../public/Logo.png" height="150" width="150"/></a>
            <ul class="uk-navbar-nav">
                <li><a href="">Work</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Story</a></li>
                <li><a href="">Shop</a></li>
                <li><a href="">Gallery</a></li>
                <li><a href="">Contact</a></li>
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

  .uk-logo {display: inline-block;}
  .uk-navbar-nav {
      list-style: none;
      margin: 0;
      padding: 0;
      float: right;
  }

  .uk-navbar-nav li {display: inline-block;}
  .uk-navbar-nav a {
      text-decoration: none;
      display: block;
      position: relative;
      line-height: 61px;
      padding-left: 20px;
      font-size: 18px;
      letter-spacing: 2px;
      font-family: 'Arimo', sans-serif;
      font-weight: bold;
      color: black;
      transition: .3s linear;
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