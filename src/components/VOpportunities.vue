<script setup>
// const opportunities = [
//     {
//         img: {
//             src: '/message.svg',
//             alt: 'msg',
//         },
//         title: 'Общение с классом',
//         description: 'Видеосвязь Чат с классом',
//     },
//     {
//         img: {
//             src: '/tv.svg',
//             alt: 'telev',
//         },
//         title: 'Проведение занятий',
//         description: 'Презентация файлов Демонстрация экрана',

//     },
//     {
//         img: {
//             src: '/yesorno.svg',
//             alt: 'yon',
//         },
//         title: 'Посещаемость',
//         description: 'Автоматическое отслеживание присутствующих',
//     },
//     {
//         img: {
//             src: '/time.svg',
//             alt: 'tme',
//         },
//         title: 'История занятий',
//         description: 'Материалы урока',
//     },
// ]
</script>

<template>
    <section class="opportunities">
        <div class="container">
            <h1>Возможности</h1>
            <div class="withOut__swiper">
                <div class="row">
                    <div class="col-xl-3 col-md-6">
                        <div class="opportunities__card1">
                            <div class="opportunities__card-message">
                                <img src="/message.svg" alt="" />
                            </div>
                            <h3>Общение с классом</h3>
                            <p>Видеосвязь Чат с классом</p>
                        </div>
                    </div>
                    <div class="col-xl-3 col-md-6">
                        <div class="opportunities__card2">
                            <div class="opportunities__card-tv">
                                <img src="/tv.svg" alt="" />
                            </div>
                            <h3>Проведение занятий</h3>
                            <p>
                                Презентация файлов <br />
                                Демонстрация экрана
                            </p>
                        </div>
                    </div>
                    <div class="col-xl-3 col-md-6">
                        <div class="opportunities__card3">
                            <div class="opportunities__card-yesorno">
                                <img src="/yesorno.svg" alt="" />
                            </div>
                            <h3>Посещаемость</h3>
                            <p>
                                Автоматическое <br />
                                отслеживание <br />
                                присутствующих
                            </p>
                        </div>
                    </div>
                    <div class="col-xl-3 col-md-6">
                        <div class="opportunities__card4">
                            <div class="opportunities__card-time">
                                <img src="/time.svg" alt="" />
                            </div>
                            <h3>История занятий</h3>
                            <p>Материалы урока</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="swiper mySwiper">
                <div class="swiper-wrapper">
                    <div class="swiper-slide">
                        <div class="opportunities__card1">
                            <div class="opportunities__card-message">
                                <img src="/message.svg" alt="" />
                            </div>
                            <h3>Общение с классом</h3>
                            <p>
                                Видеосвязь <br />
                                Чат с классом
                            </p>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="opportunities__card2">
                            <div class="opportunities__card-tv">
                                <img src="/tv.svg" alt="" />
                            </div>
                            <h3>Проведение занятий</h3>
                            <p>
                                Презентация файлов <br />
                                Демонстрация экрана
                            </p>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="opportunities__card3">
                            <div class="opportunities__card-yesorno">
                                <img src="/yesorno.svg" alt="" />
                            </div>
                            <h3>Посещаемость</h3>
                            <p>
                                Автоматическое <br />
                                отслеживание <br />
                                присутствующих
                            </p>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="opportunities__card4">
                            <div class="opportunities__card-time">
                                <img src="/time.svg" alt="" />
                            </div>
                            <h3>История занятий</h3>
                            <p>Материалы урока</p>
                        </div>
                    </div>
                </div>
                <div class="swiper-pagination"></div>
            </div>
        </div>
    </section>
</template>

<style scoped></style>