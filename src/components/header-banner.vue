<template lang="html">
  <div>
    <div class="container__banner">
      <div class="header">
        <div class="logo"></div>
      </div>
      <div class="mobile__container">
        <div class="mobile__content">
          <h1 class="title">Получай ежедневные сигналы рынка акций</h1>
          <a href="#" class="app__store__ico">
            <img src="../assets/img/app-store-ico.svg">
          </a>
        </div>
        <div class="mobile__image">
          <img src="../assets/img/mobile-image.png"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'header-banner',
};
</script>

<style scoped lang="scss">
  .mobile__container {
    display: flex;
    align-items: center;
  }

  .title {
    font-style: normal;
    font-weight: normal;
    font-size: 47px;
    line-height: 55px;
    text-align: left;
    margin: 0 0 70px;
  }

  .mobile__image {
    width: 50%;
  }
  .container__banner {
    padding-top: 40px;
    margin-bottom: 48px;
    &:before {
      content: "";
      position: absolute;
      width: 749.2px;
      height: 541.72px;
      background: #FFFFFF;
      opacity: 0.1;
      filter: blur(116px);
      transform: rotate(-28.08deg);
      top: -60%;
      left: 0;
      right: 0;
      margin: auto;
    }
  }
  .logo {
    width: 45px;
    height: 45px;
    left: 120px;
    background: #3D3E44 url("../assets/img/K-logo.svg")no-repeat bottom left;
    background-size: 25px 26px;
    border-radius: 5px;
  }
</style>
