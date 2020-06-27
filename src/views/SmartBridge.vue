<template>
  <div class='bridge'>
    <img class='logo' src="../assets/smartBridge/logo.png" alt="">
    <div class='wrapper'> 
      <div class='part1'>
        <p class='part1__title'>Smart Bridge</p>
        <p class='part1__description'>Задача : Разработать платформу для <br> правительственных услуг. <br><br>
         Решение : Наша команда приняла участие в проекте <br> SmartBridge. Цель проекта — это создание единой <br> платформы
          для всей информации в системе и базе <br> данных государственных учреждений, обеспечение <br> взаимодействия, 
          обмена и контроля целостности <br> данных для внутренней и внешней системы.
        </p>
        <div class='part1__text-bot'>
                  <div class='part1__text-bot__detail'>
                      <img src="../assets/smartBridge/detail.png" alt="">
                  </div>
                  <div class='part1__text-bot__text'>
                      <p>Технологии: <br>Frontend – ReactJS </p>
                  </div>
              </div>

      </div>
      <div class='part2'>
        <div class='top-images'>
          <img src="../assets/smartBridge/1.png" alt="">
        <div class='with-tree'>
          <img class='top-tree' src="../assets/smartBridge/top.png" alt="">
          <img class='image3'  src="../assets/smartBridge/2.png" alt="">
        </div>
        </div>
        <div class='bottom-images'>
          <div class='with-tree'>
          <img class='bot-tree' src="../assets/smartBridge/bot.png" alt="">
          <img src="../assets/smartBridge/3.png" alt="">
        </div>
        <img class='image4' src="../assets/smartBridge/4.png" alt="">
        </div>
      </div>
    </div>
    <div class='side-color'>
      <a class='side-color__link' href="#">www.elefanto.kz</a>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">

.image3, .image4 {
  margin-left: 20px;
}
.top-tree, .bot-tree  {
  position: absolute;
}
.bot-tree {
  top: -123px;
}
.top-tree {
  top: -114px;
  right: 0;
}
.with-tree {
  position: relative;
}
.bottom-images, .top-images {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.top-images {
  margin-bottom: 25px;
}
.part1 {
  padding-left: 60px;
  &__description {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 23px;
    color: #1D1E27;
  }
  &__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 47px;
    letter-spacing: 0.1em;
    margin-bottom: 63px;
    color: #194985;
  }
  &__text-bot {
        display: flex;
        &__detail {
            margin-top: 29px;
            margin-right: 12px;
        }
        &__text {
            font-family: 'Roboto';
            font-style: normal;
            font-weight: bold;
            font-size: 20px;
            line-height: 23px;
            margin-top: 35px;
            color: #1D1E27;
        }
    }
}
.wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100vh;
    width: 100%;
}
.side-color {
    position: absolute;
    background: #1B3372;
    width: 651px;
    height: 100vh;
    right: 0;
    z-index: -1;
    &__link {
        position: absolute;
        color: white;
        bottom: 30px;
        right: 26px;
        color: white;
        font-family: 'Roboto';
        font-style: normal;
        font-weight: 500;
        font-size: 26px;
        line-height: 30px;
        text-decoration: none;
        &:hover {
            color: white;
            text-decoration: none;
            cursor: pointer;
        }
    }
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
p {
  margin: 0;
}
.bridge {
    position: relative;
    display: flex;
}
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
}
</style>