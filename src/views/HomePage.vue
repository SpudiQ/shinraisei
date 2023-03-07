<template>
    <div container>

        <div class="banner">
            <img src='@/assets/banner/r32_banner.png' alt="banner">
        </div>

        <div class="section">
            <img src='@/assets/other/Line5.png' alt="line">
            <h3 class="title-section">Новинки</h3>
            <img src='@/assets/other/Line5.png' alt="line">
        </div>

        <div class="section-cards">

            <router-link class="card" to="">
                <img src='@/assets/cards/r35_card.png' alt="card">
                <p class="title-card">326POWER 3D☆STAR Trunk Spoiler for Nissan R35 GT-R</p>
            </router-link>

            <router-link class="card" to="">
                <img src='@/assets/cards/r35_card.png' alt="card">
                <p class="title-card">326POWER 3D☆STAR Trunk Spoiler for Nissan R35 GT-R</p>
            </router-link>

            <router-link class="card" to="">
                <img src='@/assets/cards/r35_card.png' alt="card">
                <p class="title-card">326POWER 3D☆STAR Trunk Spoiler for Nissan R35 GT-R</p>
            </router-link>

        </div>

        <div class="section">
            <img src='@/assets/other/Line.png' alt="line">
        </div>

        <div class="section-cards">

            <router-link class="card-brand" to="">
                <img src='@/assets/cards/greddy_card.png' alt="card">
            </router-link>

            <router-link class="card-brand" to="">
                <img src='@/assets/cards/326power_card.png' alt="card">
            </router-link>

            <router-link class="card-brand" to="">
                <img src='@/assets/cards/work_card.png' alt="card">
            </router-link>

        </div>

        <div class="section">
            <img src='@/assets/other/Line5.png' alt="line">
            <h3 class="title-section">Категории</h3>
            <img src='@/assets/other/Line5.png' alt="line">
        </div>

        <div class="section-cards">

            <router-link class="card" to="">
                <img src='@/assets/cards/bodykit.png' alt="card">
                <p class="title-card">Комплекты обвесов</p>
            </router-link>

            <router-link class="card" to="">
                <img src='@/assets/cards/spoiler.png' alt="card">
                <p class="title-card">Спойлеры</p>
            </router-link>

            <router-link class="card" to="">
                <img src='@/assets/cards/wheels.png' alt="card">
                <p class="title-card">Диски</p>
            </router-link>

        </div>

        <div class="section">
            <img src='@/assets/other/Line.png' alt="line">
        </div>

        <div class="section-about container">

            <div class="text-block">
                <h2 class="title-about">Shinraisei</h2>
                <p class="text-about">Магазин автозапчастей и тюнинга</p>
                <p class="text-about">Адрес: ул. д.</p>
                <div>
                    <label>Электронная почта:</label>
                    <a href="mailto:shinransei@gmail.com"> shinransei@gmail.com</a>
                </div>
                <div class="text-block-about">
                    <label>Номер телефона:</label>
                    <a href="tel:+7911999999"> +7 911-999-99-99</a>
                </div>
                <p class="text-about gray">Senraisei</p>
            </div>

            <div class="maps">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m17!1m12!1m3!1d1998.8615400720619!2d30.334019616201893!3d59.93443966939931!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zNTnCsDU2JzA0LjAiTiAzMMKwMjAnMTAuNCJF!5e0!3m2!1sru!2sru!4v1678109642879!5m2!1sru!2sru"
                    width="800" height="480" style="border:0; padding-bottom: 50px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                </iframe>
            </div>

        </div>

    </div>
</template>
<script>
export default {

}
</script>
<style scoped>

a {
    text-decoration: none;
    color: #fff;
}
.container {
    max-width: 1410px;
    padding: 15px;
    margin: 0 auto;
    box-sizing: content-box;
}

.banner {
    display: flex;
    justify-content: center;
}

.section {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 50px;
}

.title-section {
    font-size: 28px;
    padding-left: 33px;
    padding-right: 33px;
}

.section-cards {
    display: flex;
    flex-direction: row;
    justify-content: center;
    padding-top: 50px;
}

.card {
    text-decoration: none;
    color: #fff;
}

.card:not(:last-child) {
    padding-right: 60px;
}

.card-brand:not(:last-child) {
    padding-right: 25px;
}

.title-card {
    font-size: 16px;
    width: 380px;
    padding-top: 15px;
}

.section-about {
    display: flex;
    flex-direction: row;
    justify-content: center;
    padding-top: 50px;
}

.text-block {
    padding-right: 32px;
}

.text-about {
    padding-bottom: 50px;
}

.gray {
    padding-top: 50px;
    color: #818181;
}


</style>