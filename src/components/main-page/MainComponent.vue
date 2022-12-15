<template>
    <div class="banner__container">
        <div class="banner__text">
            <div class="banner__title">Добро
                пожаловать!
            </div>
            <div class="banner__description">Мы готовы предложить Вам лучшие стройматериалы, доступные
                цены и качественное
                обслуживание. Бесплатная доставка до двери в любой город России и возможность оплаты онлайн или при
                получении.
                Гарантия на все товары - 1 год.</div>
            <div class="pl-10 w-xs pt-5">
                <div class="banner__btn">
                    Перейти к покупкам
                    <ArrowIcon class="banner__btn-icon" />
                </div>
            </div>
        </div>
        <div class="banner"><img src="../../../public/photos/banner.jpg"></div>
    </div>
    <div class="main__container">
        <div class="main__categories">
            <div class="main__title">ПОПУЛЯРНЫЕ КАТЕГОРИИ</div>
        </div>
        <div class="main__choice">
            <div class="main__title">
                ПОЧЕМУ ВЫБИРАЮТ НАС
            </div>
            <div class="grid__items">
                <div class="grid__item">
                    <div class="grid__icon-handshake">
                        <HandshakeIcon />
                    </div>
                    <div class="grid__item-text">Надежные поставщики материалов и компонентов</div>
                </div>
                <div class="grid__item">
                    <div class="grid__icon-calendar">
                        <CalendarIcon />
                    </div>
                    <div class="grid__item-text">Опыт работы с крупными коммерческими фирмами с 2011 года</div>
                </div>
                <div class="grid__item">
                    <div class="grid__item-icon">
                        <WarehouseIcon />
                    </div>
                    <div class="grid__item-text">Большие объемы складских запасов всегда в наличии </div>
                </div>
                <div class="grid__item">
                    <div class="grid__icon-quality">
                        <DoneIcon />
                    </div>
                    <div class="grid__item-text">Контроль качества и гарантия </div>
                </div>
                <div class="grid__item">
                    <div class="grid__item-icon">
                        <WorkersIcon />
                    </div>
                    <div class="grid__item-text">Штат квалифицированных сотрудников</div>
                </div>
                <div class="grid__item">
                    <div class="grid__item-icon">
                        <CostIcon />
                    </div>
                    <div class="grid__item-text">Ценовая политика</div>
                </div>
            </div>
        </div>
        <div class="main__about" id="about">
            <div class="main__about-container">
                <div class="main__title">
                    НЕМНОГО О
                    НАШЕЙ КОМПАНИИ
                </div>
                <div class="main__description">
                    <div>«Мега Сити» работает в городе Воронеж и регионе с 2011 года, предлагая клиентам
                        производство и монтаж металлоконструкций, резервуаров, емкостей, трубопроводов и занимаемся
                        сервисом
                        продажи стройматериалов. С каждым годом мы
                        совершенствуем
                        собственные производственные мощности, налаживаем связи с новыми поставщиками сырья, применяем
                        новые
                        технологии и повышаем квалификацию каждого своего сотрудника.
                    </div>

                    <div>Среди наших клиентов такие крупные заказчики, как: Дрожжевой завод города Воронеж, Воронежский
                        шинный
                        завод, компания Vaderstad, Тепличный комплекс ООО «Агроразвитие» в Хлевенском районе Липецкой
                        области,
                        завод по
                        производству дрожжей ООО «АнгелИст Рус» в городе Данкове Липецкой области, торговый центр «Твой
                        дом»
                        и
                        другие.</div>

                    <div>Мы с радостью доставим Ваши товары точно в срок и поможем с выбором стройматериалов!</div>
                </div>
                <div class="main__photos">
                    <div class="main__photo">
                        <img src="../../../public/photos/main/main1.png">
                    </div>
                    <div class="main__photo">
                        <img src="../../../public/photos/main/main2.png">
                    </div>
                    <div class="main__photo">
                        <img src="../../../public/photos/main/main3.png">
                    </div>
                </div>
            </div>
        </div>
        <div class="main__form">
            <div class="main__title">ФОРМА ОБРАТНОЙ СВЯЗИ</div>
            <div class="main__form-container">
                <div class="main__form-description">Если у Вас есть какие-либо предложения или
                    вопросы по
                    заказу, то
                    воспользуйтесь нашей формой
                    обратной связи. Мы обязательно свяжемся с вами в ближайшее время!</div>
            </div>
            <FormComponent />
            <div class="main__form-consent">Нажимая на кнопку «Отправить», вы
                соглашаетесь на
                обработку
                персональных
                данных в
                соответствии с
                пользовательским соглашением</div>
        </div>
    </div>

</template>

<script lang="js">
import FormComponent from '../main-page/FormComponent.vue'
import HandshakeIcon from '../main-page/components/HandshakeIcon.vue'
import CalendarIcon from '../main-page/components/CalendarIcon.vue'
import CostIcon from '../main-page/components/CostIcon.vue'
import DoneIcon from '../main-page/components/DoneIcon.vue'
import WarehouseIcon from '../main-page/components/WarehouseIcon.vue'
import WorkersIcon from '../main-page/components/WorkersIcon.vue'
import ArrowIcon from '../main-page/components/ArrowIcon.vue'

export default {
    components: {
        FormComponent,
        HandshakeIcon,
        CalendarIcon,
        CostIcon,
        DoneIcon,
        WarehouseIcon,
        WorkersIcon,
        ArrowIcon,
    }
}
</script>

<style scoped>
.main__container {
    @apply flex flex-col gap-10 w-full justify-center items-center
}

.main__choice {
    width: 80%;
}

.main__choice {
    @apply flex flex-col justify-center items-center
}


.main__about {
    @apply bg-gray-200 w-full flex flex-col justify-center items-center
}

.main__about-container {
    width: 80%
}

.main__about-container {
    @apply flex flex-col justify-center items-center pt-10 pb-10
}

.main__photos {
    @apply flex flex-row gap-12 justify-center items-center pt-10
}

.main__photo {
    @apply opacity-60 hover: opacity-100
}

.main__photo {
    transition: 1s;
}

.main__title {
    @apply text-4xl font-black text-center cursor-default
}

.main__description {
    @apply text-sm flex flex-col gap-2 mt-10 cursor-default
}

.grid__items {
    @apply grid grid-rows-2 grid-cols-3 gap-x-4 gap-y-20 mt-10
}

.grid__item {
    @apply flex flex-col justify-center items-center
}

.grid__item-icon {
    @apply text-8xl hover: (opacity-60)
}

.grid__icon-handshake {
    @apply text-7xl pb-6 hover: (opacity-60)
}

.grid__icon-calendar {
    @apply text-8xl hover: (opacity-60)
}

.grid__icon-quality {
    @apply text-7xl pb-5 hover: (opacity-60)
}

.grid__item-text {
    @apply text-center cursor-default
}


.main__form {
    @apply pb-10
}

.main__categories {
    @apply bg-gray-200 w-full flex flex-col justify-center items-center pt-10
}

.banner__container {
    @apply flex flex-col justify-center items-start
}

.banner__text {
    @apply absolute text-white px-20 pl-40 cursor-default
}

.banner__title {
    @apply text-5xl border-6 border-l-yellow-400 border-t-0 border-r-0 border-b-0 p-4 cursor-default
}

.banner__description {
    @apply pt-3 pl-10 w-3xl border-6 border-r-yellow-400 border-t-0 border-l-0 border-b-0
}

.banner__btn {
    @apply py-2 px-10 bg-yellow-500 text-white cursor-pointer hover: (bg-yellow-400) active:(bg-yellow-600) flex flex-row gap-2 justify-center items-center
}

.banner__btn {
    transition: 0.5s
}

.banner__btn-icon {
    @apply text-2xl
}

.main__form-container {
    @apply mt-10
}

.main__form-description {
    @apply text-sm cursor-default
}

.main__form-consent {
    @apply text-xs text-center pt-2 cursor-default
}
</style>