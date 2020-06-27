<template>
  <div claas='soyleu'>
    <div class='soyleu__wrapper'>
        <div class='part1'>
            <p class='part1__title'>Soyleu</p>
            <p class='part1__description'>Задача : Создание мобильного приложения <br> для изучения казахского языка.<br><br>
             Решение : нами было разработано мобильное приложение <br>по изучению казахского языка при помощи геймификации.<br>
              Обучение казахскому языку проводится на<br> базе латинской графики.
            </p>
            <div class='bot-text'>
                <div class='bot-text__detail'>
                    <img src="../assets/smartBridge/detail.png" alt="">
                </div>
                <div class='bot-text__text'>
                    <p>Технологии:<br> Backend – Python<br> Frontend – Android(Kotlin), iOS(Swift)<br> Design – Adobe XD </p>
                </div>
            </div>
        </div>
        <div class='side-color'>
            <div class='side-color__mobile-images'>
                <div class='side-color__mobile-images__fir-row'>
                    <img src="../assets/soyleu/1.png" alt="">
                    <img src="../assets/soyleu/2.png" alt="">
                </div>
                <div class='side-color__mobile-images__sec-row'>
                    <img src="../assets/soyleu/3.png" alt="">
                    <img src="../assets/soyleu/4.png" alt="">
                </div>
            </div>
            <div class='side-color__background-cubes'>
                <img class='side-color__background-cubes__cube1' src="../assets/soyleu/5.png" alt="">
                <img  src="../assets/soyleu/6.png" alt="">
                <img class='side-color__background-cubes__cube3' src="../assets/soyleu/7.png" alt="">
                <img src="../assets/soyleu/8.png" alt="">
            </div>
            <a class='website-link' href="#">www.elefanto.kz</a>
        </div>
    </div>
    <img class='logo' src="../assets/jforum/logo.png" alt="">
  </div>
</template>


<style scoped lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
p {
  margin: 0;
}
.soyleu {
    position: relative;
    display: flex;
    &__wrapper {
        height: 100vh;
        display: flex;
        position: relative;
        align-items: center;
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
        margin-bottom: 63px;
        letter-spacing: 0.1em;
        color: #86A2F4;
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
.bot-text {
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
.side-color {
    display: flex;
    position: absolute;
    height: 100vh;
    width: 720px;
    right: 0;
    background: linear-gradient(144.19deg, #82A9F0 8.15%, #918AF5 86.7%);
    padding-left: 148px;
    z-index: -1;
    &__mobile-images {
        display: flex;
        width: 387px;
        &__fir-row, &__sec-row {
            display: flex;
            flex-direction: column;
        }
        &__sec-row {
            margin-top: 80px;
        }
    }
    &__background-cubes {
        position: absolute;
        right: 0;
        display: flex;
        flex-direction: column;
        align-items: flex-end;
        z-index: -1;
        &__cube1, &__cube3 {
            margin-right: 70px;
        }
    }
}
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
}
.website-link {
    position: absolute;
    bottom: 30px;
    right: 26px;
    text-decoration: none;
    color: white;
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 500;
    font-size: 26px;
    line-height: 30px;
    &:hover {
        color: white;
        text-decoration: none;
        cursor: pointer;
    }
}
</style>