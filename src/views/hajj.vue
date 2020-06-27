<template>
    <div class='hajj'>
        <div class='text'>
            <img class='logo' src="../assets/deni/logo.png" alt="">
            <div class='wrapper'>
                <div class='wrapper__text'>
                    <p class='wrapper__text__title'>Hajj & Umrah</p>
                    <p class='wrapper__text__description'>
                        Задача : Разработка мобильного приложения для <br> туристического агентство Хикмет.<br><br>
                        Решение : Мы сделали приложение, которое<br> поможет вам совершать Хадж и Умру самыми<br>
                        творческими способами. Здесь собраны сотни Дуа <br>и Зикр из Корана и Сунны, которые вы 
                        сможете выучить <br>или прочитать в любое время. Контрольный список<br> Рамадана поможет
                        вам провести священный месяц<br> Рамадан продуктивно и осознанно. Выбирай свои цели <br>
                        и следи за собой, увеличивай свое благочестие!
                    </p>
                    <div class='tech'>
                        <div class='tech__detail'>
                            <img src="../assets/smartBridge/detail.png" alt="">
                        </div>
                        <div class='tech__text'>
                            <p>
                                Технологии:<br> Backend – Python<br> Frontend – Android(Kotlin), iOS(Swift)
                            </p>
                        </div>
                    </div>
                </div>
                <div class='wrapper__mobile'>
                    <img src="../assets/hajj/1.png" alt="">
                </div>
            </div>
        </div>
        <div class='image'>
            <img class='star' src="../assets/hajj/star.png" alt="">
            <div class='phones'>
                <div class='phones__first-row'>
                    <img class='first-phone' src="../assets/hajj/2.png" alt="">
                    <img src="../assets/hajj/2.png" alt="">
                </div>
                <div class='phones__second-row'>
                    <div>
                        <img class='second-phone' src="../assets/hajj/2.png" alt="">
                        <img class='third-phone' src="../assets/hajj/2.png" alt="">
                    </div>
                    <div>
                        <img class='mobile' src="../assets/hajj/2.png" alt="">
                        <img class='mobile' src="../assets/hajj/2.png" alt="">
                    </div>
                </div>
            </div>
            <img class='house' src="../assets/hajj/house.png" alt="">
            <a class=link href="#">www.elefanto.kz</a>
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
.hajj {
    position: relative;
    display: flex;
    height: 100vh;
}
.text {
    position: relative;
    height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
}
.wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 700px;
    width: 100%;
    padding: 0 300px 0 60px;
    &__text {
        &__title {
            font-family: 'Roboto';
            font-style: normal;
            font-weight: bold;
            font-size: 40px;
            line-height: 47px;
            margin-bottom: 62px;
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
    &__detail {
        margin-right: 12px;
        margin-top: 42px;
    }
    &__text {
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 23px;
        margin-top: 48px;
        color: #1D1E27;

    }
}
.image {
    position: absolute;
    display: flex;
    align-items: flex-end;
    right: 0;
    z-index: -1;
    width: 615px;
    height: 100vh;
    background: linear-gradient(139.81deg, #5B6D92 8.15%, #353B65 86.7%);
}
.phones {
    display: flex;
    justify-content: space-between;
    width: 100%;
    margin-bottom: 90px;
    &__first-row {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
}
.first-phone{
    margin-bottom: 13px;
}
.third-phone, .second-phone {
    margin-bottom: 14px;
    margin-left: 15px;
}
.logo {
    position: absolute;
    top: 30px;
    left: 60px;
}
.mobile {
    margin-left: 15px;
}
.house {
    position: absolute;
    height: 281px;
    top: 30px;
    right: 0;
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
.star {
    position: absolute;
    padding: 15px;
    background: #FFF;
    box-shadow: 0px 20px 30px rgba(45, 45, 45, 0.4);
    border-radius: 20px;
    top: 50%; 
    left: 50%; 
    transform: translate(-50%, -50%);
    left: 0;
}
</style>