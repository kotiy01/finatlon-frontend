<template>
    <header class="header">
        <div class="header__container">
            <p class="header__status-text"><strong>Статус проекта: </strong>отборочный тур</p>
            <div class="header__nav">
                <a href="" class="header__link">olimpiada@ifru.ru</a>
                <a href="" class="header__link">+7 (495) 369-04-02 доб.2</a>
                <a href="" class="header__btn header__btn-reg">Регистрация</a>
                <a href="" class="header__btn header__btn-log">Вход</a>
            </div>
        </div>
    </header>
</template>

<script>
export default {}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto+Flex:opsz,wght@8..144,100..1000&display=swap');
.header {
    width: 100%;
    height: 48px;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #e22f14;

    &__container {
        width: 1196px;
        height: 100%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
    }

    &__status-text {
        font-family: "Roboto Flex", sans-serif;
        font-size: 14px;
        color: #ffffff;
    }

    &__nav {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
    }

    &__link {
        font-family: "Roboto Flex", sans-serif;
        font-size: 14px;
        color: #ffffff;
        margin-right: 24px;
        text-decoration: none;
    }

    &__btn {
        font-family: "Roboto Flex", sans-serif;
        font-size: 14px;
        color: #ffffff;
        text-decoration: none;
        padding: 16px;
        background-color: #f1481e;

        &-reg {
            margin-left: 42px;
        }

        &-log {
            margin-left: 5px;
        }
    }
}
</style>