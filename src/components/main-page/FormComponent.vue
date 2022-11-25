<template>
    <div class="form__container">
        <div class="form__input-container">
            <input class="form__input" type="text" placeholder="Имя" />
        </div>
        <div class="form__input-container">
            <input class="form__input" type="email" placeholder="Email" />
        </div>
        <div class="form__input-container">
            <input class="form__input" type="tel" placeholder="Телефон" />
        </div>
        <div class="form__btn">
            Отправить
        </div>
    </div>
</template>

<script lang="js">
export default {
    components: {}
}
</script>

<style scoped>
.form__container {
    @apply w-full flex flex-row gap-3 justify-center items-center pt-5
}

.form__input-container {
    @apply
}

.form__input {
    @apply py-2 px-8 bg-transparent border-3 border-t-0 border-r-0 outline-none ring-0 border-l-0 border-b-gray-500 hover: (ring-0 outline-none)
}

.form__btn {
    @apply py-2 px-10 bg-blue-700 text-white cursor-pointer hover: (bg-blue-600) active:(bg-blue-800)
}

.form__btn {
    transition: 0.5s
}
</style>