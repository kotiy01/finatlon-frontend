<template>
    <footer class="footer">
        <div class="footer__container">
            <div class="footer__contacts">
                <a href="" class="footer__link footer__link_email">olimpiada@ifru.ru</a>
                <a href="" class="footer__link footer__link_number">+7 (495) 369-04-02 доб.2</a>
            </div>
            <div class="footer__developers">
                <a href="" class="footer__link-img"><img src="./assets/ИФРУ.svg" alt="" class="footer__img"></a>
                <a href="" class="footer__link-img"><img src="./assets/НИФРУ.svg" alt="" class="footer__img"></a>
                <a href="" class="footer__link-img"><img src="./assets/ФинПотребСоюз.svg" alt="" class="footer__img"></a>
                <a href="" class="footer__link-img"><img src="./assets/ИнститутЭкономики.svg" alt="" class="footer__img"></a>
                <a href="" class="footer__link-img"><img src="./assets/Политех.svg" alt="" class="footer__img"></a>
            </div>
        </div>
    </footer>
</template>

<script>
export default {}
</script>

<style lang="scss">
.footer {
    width: 100%;
    height: 190px;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #BC2112;

    &__container {
        width: 1196px;
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    &__contacts {
        align-self: flex-start;
        margin-bottom: 39px;
    }

    &__link {
        font-family: "Roboto Flex", sans-serif;
        font-size: 16px;
        font-weight: bold;
        color: #ffffff;
        margin-right: 54px;

        &_number {
            text-decoration: none;
        }
    }

    &__developers {
        width: 100%;
        height: 70px;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
    }
}
</style>