<template>
  <div class='juzent'>
      <img class='logo' src="../assets/juzent/logo.png" alt="">
      <div class='wrapper'>
          <div class='part1'>
              <p class='part1__title'>JUZENT</p>
              <p class='part1__description'> 
                  Задача : Информационный портал, цель которого - <br> продвижение Qpop индустрии в Казахстане. <br> <br>
                  Решение : В Elefanto был разработан информационный <br> портал с адаптированной версией под все устройства.
                  <br> Основными разделами данного портала являются: <br> - Медиатека -музыкальный плеер, новые релизы,
                  <br> исполнители, альбомы. <br> - Артисты - информация об артистах. <br> - Магазин -продажа продукции
                   лейблов. <br> - Концерты -система бронирование мест и покупки <br> онлайн билетов на концерт.
              </p>
              <div class='part1__text-bot'>
                  <div class='part1__text-bot__detail'>
                      <img src="../assets/juzent/detail.png" alt="">
                  </div>
                  <div class='part1__text-bot__text'>
                      <p>Технологии: <br> Backend – php <br> Frontend – VueJS <br> Design – Figma</p>
                  </div>
              </div>
          </div>
          <div class='part2'>
              <img src="../assets/juzent/5.png" alt="">
          </div>
          <div class='side-color'>
              <img class='side-color__image' src="../assets/juzent/1.png" alt="">
              <img class='side-color__image' src="../assets/juzent/2.png" alt="">
              <img class='side-color__image' src="../assets/juzent/3.png" alt="">
              <img src="../assets/juzent/4.png" alt="">
              <a class='side-color__link' href="#">www.elefanto.kz</a>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.juzent {
    position: relative;
}
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
}
.wrapper {
    position: relative;
    height: 100vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.side-color {
    position: absolute;
    height: 100vh;
    width: 581px;
    background: black;
    right: 0;
    z-index: -1;
    padding-right: 26px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    &__image {
        margin-bottom: 20px;
    }
    &__link {
        margin-top: 11px;
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
.part1 {
    padding-left: 60px;
    &__title {
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 40px;
        line-height: 47px;
        margin-bottom: 28px;
        letter-spacing: 0.1em;
        color: #171717;
    }
    &__description {
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 23px;
        color: #1D1E27;
    }
    &__text-bot {
        display: flex;
        &__detail {
            margin-top: 85px;
            margin-right: 18px;
        }
        &__text {
            font-family: 'Roboto';
            font-style: normal;
            font-weight: bold;
            font-size: 20px;
            line-height: 23px;
            margin-top: 91px;
            color: #1D1E27;
        }
    }
}
.part2 {
    margin-right: 230px;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
p {
  margin: 0;
}
</style>