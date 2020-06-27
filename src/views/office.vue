<template>
  <div class='jforum'>
    <img class='logo' src="../assets/jforum/logo.png" alt="">
    <div class='wrapper'> 
      <div class='part1'>
        <p class='part1__title'>Office 8</p>
        <p class='part1__description'>
          Задача : Первый в Казахстане сервис по поиску <br> офисной недвижимости. Мы предоставляем<br> платформу,
           которая облегчает весь процесс<br> поиска необходимого помещения. <br><br>Решение : Первый в Казахстане
            сервис по поиску офисной <br>недвижимости. Мы предоставляем платформу, которая<br> облегчает весь 
            процесс поиска необходимого помещения.<br> Собрана самая широкая база бизнес центров по всей стране.
        </p>
        <div class='part1__text-bot'>
         <div class='part1__text-bot__detail'>
            <img src="../assets/smartBridge/detail.png" alt="">
         </div>
         <div class='part1__text-bot__text'>
            <p>Технологии: <br>Backend – Phyton <br>Frontend – VueJS <br>Design – Figma </p>
         </div>
        </div>
      </div>
      <div class='part2'>
          <div class='part2__images'>
              <img src="../assets/office/1.png" alt="">
            <div class='part2__images__bot'>
              <img src="../assets/office/2.png" alt="">
              <img src="../assets/office/3.png" alt="">
              <img src="../assets/office/4.png" alt="">
            </div>
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
.part2 {
  &__images {
    display: flex;
    flex-direction: column;
    align-items: center;
    &__bot {
      margin-top: 68px;
    }
  }
}
.jforum {
  position: relative;
  display: flex;
}
.wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100vh;
    width: 100%;
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
    color: #171717;
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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
p {
  margin: 0;
}
.side-color {
    position: absolute;
    background: #6AA0F1;
    width: 581px;
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
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
}
</style>