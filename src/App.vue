<template>
  <div class="uk-background-fixed">
  <div class="uk">
      <div class="uk-card-header">
          <div class="menu">
            <ul class="uk-table-hover uk-animation-slide-top" data-uk-tab>
            <li class="uk-active"><a href="">Главная</a></li>
            <li><a href="">Сережа</a></li>
            <li><a href="">Один из этих</a></li>
            </ul>
          </div>
      </div>
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

  html, body {
    height: 100%;
    margin: 0;
    padding: 0;
    overflow: hidden;
  }
    body {
      background-color: darkgray;
    }
  ul, uk-tab {
    background-color: black;
  }

</style>