<template>
  <div class='xten'>
      <img class='logo' src="../assets/deni/logo.png" alt="">
      <div class='wrapper'>
        <div class="wrapper__text">
          <p class='wrapper__text__title'>x10 Mentorship</p>
          <p class='wrapper__text__description'>
            Задача : Первый в Казахстане сервис по поиску <br> офисной недвижимости. Мы предоставляем<br> платформу,
            которая облегчает весь процесс<br> поиска необходимого помещения.<br><br> Решение : Здесь собрана 
            самая широкая база<br> бизнес центров по всей стране.
          </p>
          <div class='tech'>
            <img src="../assets/smartBridge/detail.png" alt="">
            <p class='tech__text'>Технологии</p>
          </div> 
        </div>
        <!-- <img clas='side__main-phone' src="../assets/xten/mainphone.png" alt=""> -->
      </div>
      <div class='side'>
        <div class='side__phones'>
          <img class='side__phones__phone1' src="../assets/xten/phone1.png" alt="">
          <div class='side__phones__right'>
            <img class='side__phones__right__group' src="../assets/xten/phone2.png" alt="">
            <img class='side__phones__right__group' src="../assets/xten/phone3.png" alt="">
            <img class='side__phones__right__group' src="../assets/xten/phone4.png" alt="">
            <img class='side__phones__right__group' src="../assets/xten/phone5.png" alt="">
          </div>
        </div>
        <img class='side__main-phone' src="../assets/xten/mainphone.png" alt="">
        <div class='side__curve'>
          <img class='side__curve__plant1' src="../assets/xten/1.png" alt="">
          <img class='side__curve__plant2' src="../assets/xten/2.png" alt="">
          <img class='side__curve__plant3' src="../assets/xten/3.png" alt="">
        </div>
        <a class='link' href="#">www.elefanto.kz</a>
        
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
p {
  margin: 0;
}
.xten {
  display: flex;
  position: relative;
  height: 100vh;
}
.wrapper {
  display: flex;
  align-items: center;
  width: 100%;
  z-index: 1;
  padding-left: 60px;
  &__text {
    &__title {
      margin-bottom: 63px;
      font-family: 'Roboto';
      font-style: normal;
      font-weight: bold;
      font-size: 40px;
      line-height: 47px;
      letter-spacing: 0.1em;
      color: #1B213E;
    }
    &__description {
      font-family: 'Roboto';
      font-style: normal;
      font-weight: bold;
      font-size: 20px;
      line-height: 23px;
      color: #1D1E27;
    }
  }
}
.tech {
  display: flex;
  align-items: center;
  margin-top: 75px;
  &__text {
    margin-left: 12px;
    font-size: 20px;
    line-height: 23px;
    color: #1D1E27;
    font-family: 'Roboto';
    font-style: normal;
    font-weight: bold;
  }
}
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
}
.side {
  position: absolute;
  padding-top: 114px;
  right: 0;
  width: 720px;
  height: 100vh;
  background: #326FEE;
  &__main-phone {
    position: absolute;
    top: 50%;
    left: 67px;
    transform: translateY(-50%);
    z-index: 999;
  }
  &__phones {
    display: flex;
    justify-content: space-between;
    &__phone1 {
      margin-left: 29px;
    }
    &__right {
      &__group {
        margin-left: 25px;
      }
    }
  }
  &__curve {
    position: absolute;
    bottom: 0;
    height: 374px;
    width: 100%;
    background: url(../assets/xten/curve.png);
    &__plant1 {
      position: absolute;
      right: 98px;
      top: -124px;
    }
    &__plant2 {
      position: absolute;
      right: 124px;
      top: -124px;
    }
    &__plant3 {
      position: absolute;
      right: 145px;
      top: -52px;
    }
  }
}
.link {
  position: absolute;
  bottom: 30px;
  right: 26px;
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 500;
  font-size: 26px;
  line-height: 0px;
  color: white;
  text-decoration: none;
  &:hover {
    color: white;
    text-decoration: none;
    cursor: pointer;
  }
}
</style>