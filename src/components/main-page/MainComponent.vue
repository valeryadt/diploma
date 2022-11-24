<template>
    <!-- <SwiperComponent /> -->
    <div class="main__container">
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
                    <div class="grid__text-quality">Контроль качества и гарантия </div>
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
        <div class="main__about">
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
            <div class="mt-10">
                <div class="main__form-description text-sm">Если у Вас есть какие-либо предложения или вопросы по
                    заказу, то
                    воспользуйтесь нашей формой
                    обратной связи. Мы обязательно свяжемся с вами в ближайшее время!</div>
            </div>
            <FormComponent />
            <div class="text-xs text-center">Нажимая на кнопку «Отправить», вы соглашаетесь на обработку персональных
                данных в
                соответствии с
                пользовательским соглашением</div>
        </div>
    </div>

</template>

<script lang="js">
import SwiperComponent from '../main-page/SwiperComponent.vue'
import FormComponent from '../main-page/FormComponent.vue'
import HandshakeIcon from '../main-page/components/HandshakeIcon.vue'
import CalendarIcon from '../main-page/components/CalendarIcon.vue'
import CostIcon from '../main-page/components/CostIcon.vue'
import DoneIcon from '../main-page/components/DoneIcon.vue'
import WarehouseIcon from '../main-page/components/WarehouseIcon.vue'
import WorkersIcon from '../main-page/components/WorkersIcon.vue'


export default {
    components: {
        SwiperComponent,
        FormComponent,
        HandshakeIcon,
        CalendarIcon,
        CostIcon,
        DoneIcon,
        WarehouseIcon,
        WorkersIcon
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
    @apply opacity-50 hover: opacity-100
}

.main__title {
    @apply text-4xl font-black text-center
}

.main__description {
    @apply text-sm flex flex-col gap-2 mt-10
}

.grid__items {
    @apply grid grid-rows-2 grid-cols-3 gap-x-4 gap-y-20 mt-10
}

.grid__item {
    @apply flex flex-col justify-center items-center
}

.grid__item-icon {
    @apply text-8xl
}

.grid__icon-handshake {
    @apply text-7xl pb-6
}

.grid__icon-calendar {
    @apply text-8xl
}

.grid__icon-quality {
    @apply text-7xl pb-5
}

.grid__item-text {
    @apply text-center
}

.grid__text-quality {
    @apply text-center
}
</style>