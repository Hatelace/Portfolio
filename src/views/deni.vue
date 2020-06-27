<template>
  <div class='deni'>
    <img class='logo' src="../assets/deni/logo.png" alt="">
    <div class='wrapper'>
      <!-- part1 -->
      <div class="part1">
        <p class='part1__title'>Deni Coffee</p>
        <p class='part1__description'>
          Задача : Первый в Казахстане сервис по поиску <br> офисной недвижимости. Мы предоставляем <br> платформу, которая
          облегчает весь процесс<br> поиска необходимого помещения. <br><br> Решение : Здесь собрана самая широкая база <br>
          бизнес центров по всей стране.
        </p>
        <div class='part1__text-bot'>
          <div class='part1__text-bot__detail'>
            <img src="../assets/deni/detail.png" alt="">
          </div>
          <div class='part1__text-bot__text'>
            <p>Технологии: <br> Здесь собрана самая широкая база <br> бизнес центров по всей стране.</p>
          </div>
        </div>
      </div>
      <!-- part2 -->
      <div class="part2">
        <div class='part2__top'>
          <div class='part2__top__image'>
            <img src="../assets/deni/1.png" alt="">
            <img class='circle_top' src="../assets/deni/circle1.png" alt="">
          </div>
          <img class='last-image' src="../assets/deni/2.png" alt="">
        </div>
        <div class='part2__bot'>
          <div class='part2__bot__image'>
            <img src="../assets/deni/3.png" alt="">
            <img class='circle_bot' src="../assets/deni/circle2.png" alt="">
          </div>
          <img class='last-image' src="../assets/deni/4.png" alt="">
        </div>
      </div>
    </div>
    <div class='side-color'>
      <a class='link' href="#">www.elefanto.kz</a>
      <img class='coffee-beans' src="../assets/deni/coffee.png" alt="">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.deni {
  position: relative;
  display: flex;
  height: 100vh;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
p {
  margin: 0;
}
.part1 {
  padding-left: 60px;
  &__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 47px;
    letter-spacing: 0.1em;
    color: #FFC800;
  }
  &__description {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 23px;
    margin-top: 63px;
    color: #1D1E27;
  }
  &__text-bot {
    display: flex;
    &__detail {
      margin-top: 75px;
      margin-right: 12px;
    }
    &__text {
      margin-top: 81px;
      font-family: 'Roboto';
      font-style: normal;
      font-weight: bold;
      font-size: 20px;
      line-height: 23px;
      color: #1D1E27;
    }
  }
}
.wrapper {
  align-items: center;
  display: flex;
  width: 100%;
  justify-content: space-between;
}
.part2 {
  &__top {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    margin-bottom: 25px;
    &__image {
      position: relative;
    }
  }
  &__bot {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    &__image {
      position: relative;
    }
  }
}
.circle_bot {
  position: absolute;
  padding: 10px;
  border-radius: 50%;
  background: white;
  top: -25px;
  left: -25px;
  box-shadow: 0px 30px 60px rgba(138, 149, 158, 0.2);
}
.circle_top {
  position: absolute;
  padding: 10px;
  top: -50px;
  left: -40px;
  border-radius: 50%;
  box-shadow: 0px 30px 60px rgba(138, 149, 158, 0.2);
}
.last-image {
  margin-left: 20px;
}



// logo/link/side-color
.side-color {
  position: absolute;
  width: 651px;
  height: 100vh;
  background: #FFC800;
  z-index: -1;
  right: 0;
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
.coffee-beans {
  position: absolute;
  height: 208px;
  left: -114px;
  bottom: 0;
}
</style>