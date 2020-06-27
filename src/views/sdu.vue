<template>
  <div claas='soyleu'>
    <div class='soyleu__wrapper'>
        <div class='part1'>
            <p class='part1__title'>SDU</p>
            <p class='part1__description'>
                Задача : Разработка мобильного приложения <br> для объедение всех выпускников ВУЗа  <br> <br>
                Решение : было сделано мобильное приложение для ассоциации <br> выпускников университета им. 
                Сулеймана Демиреля с адаптивной  <br>версией под все мобильные устройства, которое предоставит 
                 <br>пользователю возможность переписываться, загружать объявления <br> и просматривать вакансии 
                 на работу, а также доступ  <br>ко всей базе выпускников.
            </p>
            <div class='bot-text'>
                <div class='bot-text__detail'>
                    <img src="../assets/smartBridge/detail.png" alt="">
                </div>
                <div class='bot-text__text'>
                    <p>Технологии:<br> Backend – Python<br> Frontend – Android, iOS(React Native)<br> Design – Adobe XD </p>
                </div>
            </div>
        </div>
        <div class='side-color'>
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
        margin-top: 29px;
        margin-right: 12px;
    }
    &__text {
        margin-top: 35px;
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
    width: 615px;
    right: 0;
    background: linear-gradient(144.19deg, #82A9F0 8.15%, #918AF5 86.7%);
    z-index: -1;
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