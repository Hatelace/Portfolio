<template>
<div class='main'>
    <img class='logo' src="../assets/jforum/logo.png" alt="">
    <div class='main__wrapper'>
        <div class='main__wrapper__part1'>
            <p class='main__wrapper__part1__title'>Calendario</p>
            <p class='main__wrapper__part1__description'>Задача : Создание мобильного приложения для <br> повышения 
            эффективности сотрудников.<br><br> Решение : Корпоративный органайзер и чат-мессенджер <br>для компании 
            Allageum Electrics. Основными функциями<br> которого являются: быстрая и удобная коммуникация<br> сотрудников, 
            а также отслеживание эффективности.</p>
            <div class='bot-text'>
                <div class='bot-text__detail'>
                    <img src="../assets/smartBridge/detail.png" alt="">
                </div>
                <div class='bot-text__text'>
                    <p>Технологии:<br> Backend – Python<br> Frontend – Android(Kotlin), iOS(Swift)<br> Design – Adobe XD </p>
                </div>
            </div>
        </div>
        <div class='main__wrapper__part2'>
            <img src="../assets/calendario/3.png" alt="">
            <img class='main__wrapper__part2__last-image' src="../assets/calendario/4.png" alt="">
        </div>
    </div>
    <div class='side-color'>
        <div class='side-color__background-images'>
            <img class='side-color__background-images__first-image' src="../assets/calendario/1.png" alt="">
            <img src="../assets/calendario/2.png" alt="">
        </div>
        <a class='website-link' href="#">www.elefanto.kz</a>
    </div>
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
.main {
    position: relative;
    display: flex;
    height: 100vh;
    &__wrapper {
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        &__part1 {
            padding-left: 60px;
            &__title {
                margin-bottom: 63px;
                font-family: 'Roboto';
                font-style: normal;
                font-weight: bold;
                font-size: 40px;
                line-height: 47px;
                letter-spacing: 0.1em;
                color: #4E73B5;
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
        &__part2 {
            &__last-image {
                margin-right: 26px;
                margin-left: 104px;
            }
        }
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
    position: absolute;
    height: 100vh;
    width: 720px;
    right: 0;
    background: #4E73B5;
    padding-top: 121px;
    padding-left: 33px;
    z-index: -1;
    &__background-images {
        display: flex;
        align-items: center;
        &__first-image {
            margin-right: 105px;
        }
    }
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
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
}

</style>