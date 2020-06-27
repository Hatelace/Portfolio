<template>
  <div class='qos'>
      <img class='logo' src="../assets/deni/logo.png" alt="">
      <div class='text'>
          <p class='text__title'>QOS</p>
          <p class='text__desc'>
              Задача : Мобильное приложение на платформах <br> iOS и Android, цель которого - продвижение Qpop <br>
              индустрии в Казахстане.<br><br> Решение : Был разработан мобильное приложение <br>на такие платформы, 
              как iOS и Android.<br> Основными разделами данного приложения являются:<br> - Медиатека -музыкальный плеер, 
              новые релизы, <br>исполнители, альбомы. <br>- Артисты - информация об артистах.<br> - Магазин -продажа 
              продукции лейблов.<br> - Концерты -система бронирование мест и покупки <br>онлайн билетов на концерт.
          </p>
          <div class='tech'>
            <div class='tech__detail'>
                <img src="../assets/smartBridge/detail.png" alt="">
            </div>
            <div>
                <p class='tech__text'>
                    Технологии: <br> Backend – Python <br> Frontend – Android(Kotlin), iOS(Swift) <br> Design – Figma 
                </p>
            </div>
          </div>
      </div>
      <div class='phones'>
          <div class='phones__cols'>
            <img src="../assets/qos/1.png" alt="">
            <img class='phones__cols__bot' src="../assets/qos/2.png" alt="">
          </div>
          <div class='phones__cols mid-phones'>
            <img src="../assets/qos/3.png" alt="">
            <img class='phones__cols__middle' src="../assets/qos/4.png" alt="">
          </div>
          <div class='phones__cols'>
            <img src="../assets/qos/5.png" alt="">
            <img class='phones__cols__bot' src="../assets/qos/6.png" alt="">
          </div>
      </div>
      <div class="side">
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
.qos {
    position: relative;
    display: flex;
    height: 100vh;
    justify-content: space-between;
    align-items: center;
}
.text {
    padding-left: 60px;
    &__title {
        margin-bottom: 26px;
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 40px;
        line-height: 47px;
        letter-spacing: 0.1em;
        color: #01FFFF;
    }
    &__desc {
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 23px;
        color: #1D1E27;
    }
}
.tech {
    display: flex;
    &__detail {
        margin-top: 26px;
        margin-right: 12px;
    }
    &__text {
        margin-top: 32px;
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 23px;
        color: #1D1E27;
    }
}
.phones {
    height: 100vh;
    display: flex;
    align-items: flex-start;
    &__cols {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-left: -69px;
        &__bot {
            margin-top: -59px;
        }
        &__middle {
            margin-top: -49px;
        }
    }
}
.mid-phones {
    height: 100vh;
    justify-content: space-between;
}
.side {
  position: absolute;
  right: 0;
  width: 651px;
  height: 100vh;
  background: #01FFFF;
  z-index: -1;
}
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
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