<template>
    <div class="bi">
        <img class='logo' src="../assets/deni/logo.png" alt="">
        <div class='wrapper'>
            <div class='text'>
                <p class='text__title'>CRM</p>
                <p class='text__desc'>
                    Задача : Первый в Казахстане сервис по поиску <br> офисной недвижимости. Мы предоставляем 
                    <br>платформу, которая облегчает весь процесс<br> поиска необходимого помещения.<br><br>
                    Решение : Здесь собрана самая широкая база<br> бизнес центров по всей стране.
                </p>
                <div class='tech'>
                    <img class='tech__detail' src="../assets/smartBridge/detail.png" alt="">
                    <p class='tech__text'>Технологии</p>
                </div>
            </div>
            <div class='left'>
                <div class='pictures'>
                <div class='pictures__all'>
                    <div class='pictures__all__part1'>
                        <img class='pictures__all__part1__cloud1' src="../assets/bi/big.png" alt="">
                        <img class='pictures__all__part1__cloud2' src="../assets/bi/cloud.png" alt="">
                        <img class='pictures__all__part1__birds' src="../assets/bi/birds.png" alt="">
                        <img src="../assets/bi/main.png" alt="">
                    </div>
                    <div class="pictures__all__part2">
                        <img class="pictures__all__part2__card" src="../assets/bi/1.png" alt="">
                        <img class="pictures__all__part2__card" src="../assets/bi/2.png" alt="">
                        <img class="pictures__all__part2__card" src="../assets/bi/3.png" alt="">
                        <img class="pictures__all__part2__card" src="../assets/bi/4.png" alt="">
                        <img class="pictures__all__part2__card" src="../assets/bi/5.png" alt="">
                    </div>
                </div>
            </div>
            </div>
        </div>
        <div class='side'>
            
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
.bi {
    display: flex;
    position: relative;
    height: 100vh;
}
.wrapper {
    display: flex;
    justify-content: space-between;
    width: 100%;
    align-items: center;
}
.text {
    padding-left: 60px;
    &__title {
        margin-bottom: 60px;
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 40px;
        line-height: 50px;
        letter-spacing: 0.1em;
        color: #121D38;
    }
    &__desc {
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 25px;
        color: #1D1E27;
    }
}
.tech {
    display: flex;
    align-items: center;
    margin-top: 60px;
    &__text {
        font-family: 'Roboto';
        font-style: normal;
        font-weight: bold;
        font-size: 20px;
        line-height: 23px;
        color: #1D1E27;
        margin-left: 12px;
    }
}
.pictures {
    display: flex;
    align-items: flex-start;
    width: 100%;
    height: 100vh;
    &__all {
        display: flex;
        align-items: center;
        height: 100vh;
        &__part1 {
            padding: 22px 38px;
            background: url(../assets/bi/MacBook.png) center;
            background-size: cover;
            position: relative;
            &__cloud1 {
                position: absolute;
                left: 0;
                top: -145px;
                z-index: -2;
            }
            &__cloud2 {
                position: absolute;
                right: 39px;
                top: -77px;
                z-index: -1;
            }
            &__birds {
                position: absolute;
                top: -223px;
                right: 0;
            }
        }
        &__part2 {
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            margin-left: 8px;
            padding-top: 14px;
            margin-right: 14px;
            &__card {
                margin-bottom: 22px;
            }
        }
    }
}
.side {
  position: absolute;
  right: 0;
  width: 651px;
  height: 100vh;
  background: #D1A968;
  z-index: -10;
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