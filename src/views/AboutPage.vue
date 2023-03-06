<template>
    <div class="container">

        <div class="block-about">

            <div class="block-left">

                <h1 class="title-about">Связаться с нами</h1>

                <p class="text-block-about">Есть вопросы, комментарии, предложения? Пожалуйста, напишите напрямую, используя
                    электронную почту или номер телефона ниже.</p>

                <div>
                    <label>Электронная почта:</label>
                    <a href="mailto:shinransei@gmail.com">shinransei@gmail.com</a>
                </div>

                <div class="text-block-about">
                    <label>Номер телефона:</label>
                    <a href="tel:+7911999999">+7 911-999-99-99</a>
                </div>

                <p class="text-block-about">Адрес: ул. д.</p>

                <p class="text-block-about gray">Shinraisei</p>

            </div>

            <div class="block-right">

                <div class="about-logos">

                    <img src="src/img/main-page/icons8-вконтакте-50.png" alt="vk">
                    <img src="src/img/main-page/icons8-instagram-64.png" alt="inst">
                    <img src="src/img/main-page/icons8-телеграм-48.png" alt="telegram">

                </div>

            </div>

        </div>

        <div class="maps">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m17!1m12!1m3!1d1998.8615400720619!2d30.334019616201893!3d59.93443966939931!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zNTnCsDU2JzA0LjAiTiAzMMKwMjAnMTAuNCJF!5e0!3m2!1sru!2sru!4v1678109642879!5m2!1sru!2sru"
                width="1000" height="600" style="border:0; padding-bottom: 50px;" allowfullscreen="" loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>

        <div class="line-end">

            <img src="src/img/main-page/Line1.png" alt="line">

        </div>

    </div>
</template>
<script>
export default {

}
</script>
<style scoped>

.container {
    max-width: 1410px;
    padding:  15px;
    margin: 0 auto;
    box-sizing: content-box;
}
.block-about {
    display: flex;
    justify-content: center;
    padding-top: 50px;
    padding-bottom: 30px;
}

.block-left {
    max-width: 700px;
}

.block-right {
    width: 300px;
}

.title-about {
    padding-bottom: 30px;
}

.text-block-about {
    padding-bottom: 30px;
}

.gray {
    color: #818181;
}

.about-logos {
    margin-top: 50px;
    display: flex;
    justify-content: flex-end;
}

.about-logos img {
    margin-right: 14px;
}

.maps{
    display: flex;
    justify-content: center;
}
</style>