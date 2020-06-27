<template>
  <div claas='soyleu'>
    <div class='soyleu__wrapper'>
        <div class='part1'>
            <p class='part1__title'>Tenge App</p>
            <p class='part1__description'>Задача : Разработка мобильного приложения, которое <br>проверяет 
            купюры тенге на подлинность.
            <br><br>
              Решение : Чтобы проверить подлинность купюры, <br>мы разработали мобильное приложение с 3 вариантами<br>
              проверки.<br> Список: увеличение размера купюры, просмотр через <br>ультрафиолетовые лучи, проверка водяных 
              знаков. 
            </p>
            <div class='bot-text'>
                <div class='bot-text__detail'>
                    <img src="../assets/smartBridge/detail.png" alt="">
                </div>
                <div class='bot-text__text'>
                    <p>Технологии:<br> Backend – Python<br> Frontend – Android(Java)<br> Design – Adobe XD </p>
                </div>
            </div>
        </div>
        <div class='side-color'>
            <div class='side-color__images'>
                <img class='side-color__images__first' src="../assets/tenge/1.png" alt="">
                <div class='side-color__images__middle'>
                    <img class='side-color__images__middle__big' src="../assets/tenge/big.png" alt="">
                    <img class='side-color__images__middle__tenge' src="../assets/tenge/2.png" alt="">
                    <img class='side-color__images__middle__small' src="../assets/tenge/small.png" alt="">
                </div>
                <img class='side-color__images__last' src="../assets/tenge/3.png" alt="">
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
.bot-text {
    display: flex;
    &__detail {
        margin-top: 52px;
        margin-right: 12px;
    }
    &__text {
        margin-top: 58px;
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
    background:  #AAD5C8;
    padding-top: 128px;
    padding-bottom: 258px;
    z-index: -1;
    &__images {
        position: relative;
        width: 100%;
        &__first {
            position: absolute;
            bottom: 0;
            left: 0;
            z-index: 5;
        }
        &__last {
            position: absolute;
            top: 0;
            right: 0;
            z-index: -1;
        }
        &__middle {
            margin: 154px 141px 103px 196px;
            position: relative;
            &__tenge {
                position: absolute;
                z-index: 3;
            }
            &__big {
                position: absolute;
                left: -89px;
                top: 17px;
            }
            &__small {
                position: absolute;
                right: -49px;
                z-index: 1;
            }
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