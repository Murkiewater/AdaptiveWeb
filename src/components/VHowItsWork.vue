<script setup>
const HowItsWork = [
    {
        img: {
            src: '/table.png',
            alt: 'tabl',
        },
        title: 'Составьте расписание', //отвечает за h3
        description: 'Выберите время, предмет и класс. Ученики получат уведомление о предстоящем уроке.', //овечает за p
    },
    {
        img: {
            src: '/files.svg',
            alt: 'file',
        },
        title: 'Подготовьте материал',
        description: 'Загружайте необходимые материалы к уроку.',
    },
    {
        img: {
            src: '/lesson.png',
            alt: 'less',
        },
        title: 'Начните урок с учениками',
        description: 'Задавайте вопросы и вызывайте «к доске» детей с поднятой рукой.',
    },
]
</script>

<template>
    <section class="HowItsWork">
        <div class="container">
            <div class="row">
                <h1>Как это работает?</h1>
                <div class="col-xl-4 col-lg-4 col-md-12" v-for="(item, index) in HowItsWork" :key="index">
                    <div class="tableclass">
                        <img :src="item.img.src" alt="" />
                        <h3>{{ item.title }}</h3>
                        <p>{{ item.description }}
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped></style>