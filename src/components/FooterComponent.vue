<template>
    <div class="footer">
        <div class="footer__rights">© 2022-2023 Все права защищены</div>
        <div class="footer__block">
            <div>
                <div class="footer__block-name">О КОМПАНИИ</div>
            </div>
            <div class="footer__links">
                <div>
                    <a class="footer__link">О нас</a>
                </div>
                <div>
                    <a class="footer__link">Соглашение</a>
                </div>
                <div>
                    <a class="footer__link">Свяжитесь с нами</a>
                </div>
                <div>
                    <a class="footer__link">Блог</a>
                </div>
            </div>
        </div>
        <div class="footer__block">
            <div>
                <div class="footer__block-name">СЛУЖБА ПОДДЕРЖКИ
                </div>
            </div>
            <div class="footer__links">
                <div><a class="footer__link">Мы всегда готовы помочь</a></div>
                <div><a class="footer__link">FAQ</a></div>
            </div>
        </div>
        <div class="footer__block">
            <div>
                <div class="footer__block-name">КОНТАКТЫ</div>
            </div>
            <div class="footer__links">
                <div class="footer__link-description">Телефон: <a class="footer__link">1234567890</a></div>
                <div class="footer__link-description">Email: <a class="footer__link">test@email.ru</a></div>
                <div class="footer__link-description">Местоположение: Россия, Воронеж</div>
            </div>
        </div>
        <div class="footer__sm">
            <div>
                <div class="footer__sm-text">Соц. сети</div>
            </div>
            <div class="footer__sm-icons">
                <div>
                    <VkIcon class="footer__icon-vk" />
                </div>
                <div>
                    <TwitterIcon class="footer__icon-twitter" />
                </div>
                <div>
                    <OdnoklassnikiIcon class="footer__icon-odn" />
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="js">
import VkIcon from "./icones/VkIcon.vue";
import TwitterIcon from "./icones/TwitterIcon.vue";
import OdnoklassnikiIcon from "./icones/OdnoklassnikiIcon.vue";


export default {
    name: "FooterComponent.vue",
    components: {
        VkIcon,
        TwitterIcon,
        OdnoklassnikiIcon
    }
}
</script>

<style scoped>
.footer {
    @apply w-full text-gray-300 flex justify-evenly border border-2 pt-5 pb-5 pl-2 pr-2 h-40 border-t-gray-400 border-b-0 border-r-0 border-l-0
}

.footer {
    background-color: #3a3a82
}

.footer__rights {
    @apply flex items-end cursor-default text-xs
}

.footer__block {
    @apply flex flex-col
}

.footer__block-name {
    @apply font-bold text-sm pb-4 cursor-default
}

.footer__links {
    @apply text-xs flex justify-evenly flex-col gap-1
}

.footer__link {
    @apply cursor-pointer pb-1 text-gray-300 hover: (text-white)
}

.footer__link-description {
    @apply cursor-default hover: (text-white)
}

.footer__sm {
    @apply flex justify-end flex-col cursor-default
}

.footer__sm-text {
    @apply text-center text-xs
}


.footer__sm-icons {
    @apply flex flex-row justify-between gap-1
}

.footer__sm-icon {
    @apply text-2xl cursor-pointer
}

.footer__icon-vk {
    @apply text-2xl cursor-pointer hover: (text-blue-600 bg-light-400 rounded rounded-full)
}

.footer__icon-twitter {
    @apply text-2xl cursor-pointer hover: (text-blue-500 bg-light-400 rounded rounded-full)
}

.footer__icon-odn {
    @apply text-2xl cursor-pointer hover: (text-orange-600 bg-light-300 rounded rounded-full)
}
</style>