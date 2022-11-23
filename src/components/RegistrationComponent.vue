<template>
    <div class="window__page">
        <div class="window">
            <div class="window__header">
                <div class="window__panel">
                    <div class="window__panel-hidden"></div>
                    <div class="window__panel-title">
                        Войдите или зарегистрируйтесь
                    </div>
                    <div class="window__panel-close">
                        <div class="window__close-icon"> </div>
                    </div>
                </div>
            </div>
            <div class="window__body">
                <div class="window__forms">
                    <div class="window__form">
                        <input class="window__form-input" id="inputid" name="inputName" type="text" placeholder=" " />
                        <label class="window__form-placeholder" for="inputName">Почта</label>
                    </div>
                    <div class="window__form">
                        <input class="window__form-input" id="inputid" name="inputName" type="password"
                            placeholder=" " />
                        <label class="window__form-placeholder" for="inputName">Пароль</label>
                    </div>
                </div>
                <div class="window__help">
                    <div class="window__help-txt">
                        Забыли пароль?
                    </div>
                    <div class="window__help-btns">
                        <div class="window__help-btn">
                            Продолжить
                        </div>
                    </div>
                </div>
            </div>
            <div class="window__footer">
                <div class="window__help">
                    <p class="window__help-line">Войти с помощью</p>
                </div>
                <div class="window__btns">
                    <div class="window__btn">
                        <OdnoklassnikiIcon class="window__icon-odnoklassniki" />
                        <p>Одноклассники</p>
                    </div>
                    <div class="window__btn">
                        <VkIcon class="window__icon-vk" />
                        <p>Вконтакте</p>
                    </div>
                    <div class="window__btn">
                        <TwitterIcon class="window__icon-twitter" />
                        <p>Твиттер</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script lang="js">
import OdnoklassnikiIcon from "./icones/OdnoklassnikiIcon.vue";
import VkIcon from "./icones/VkIcon.vue";
import TwitterIcon from "./icones/TwitterIcon.vue";

export default {
    components: { OdnoklassnikiIcon, VkIcon, TwitterIcon }
}
</script>
  
<style scoped>
.window {
    @apply container text-sm text-dark-300 pl-6 pr-6 h-94 w-lg flex flex-col rounded-xl bg-gradient-to-b from-neutral-100 border-gray-300 border via-neutral-200 to-neutral-300
}

.window__header {
    @apply
}

.window__panel {
    @apply border border-b-gray-800 pt-5 border-2 border-t-0 border-l-0 border-r-0 flex flex-row justify-between
}

.window__panel-title {
    @apply text-base font-bold text-md pb-1 flex items-end cursor-default
}

.window__close-icon {
    @apply cursor-pointer text-lg
}

.window__body {
    @apply flex justify-center items-start content-evenly flex-col pt-7
}

.window__forms {
    @apply flex flex-col
}

.window__form-input {
    @apply rounded-3xl h-10 w-88 border border-light-900 pl-4 bg-white mt-2
}

.window__footer {
    @apply mt-4
}

.window__forms-btn {
    @apply flex flex-col
}

.window__help {
    @apply text-gray-500 relative z-1 overflow-hidden cursor-default
}

.window__help-txt {
    @apply text-gray-500 cursor-default text-xs pt-3
}

.window__help-btns {
    @apply mt-3
}

.window__help-btn {
    @apply h-10 w-34 text-center text-xs text-white font-medium cursor-pointer flex items-center justify-center rounded-3xl bg-gray-500
}

.window__btns {
    @apply flex flex-row mt-2
}

.window__btn {
    @apply mr-2 h-10 w-52 text-center font-medium flex items-center justify-center text-black font-bold cursor-pointer rounded-2xl bg-white
}

.window__icon-odnoklassniki {
    @apply text-xl text-orange-500 mr-2
}

.window__icon-vk {
    @apply text-xl text-blue-700 mr-2
}

.window__icon-twitter {
    @apply text-xl mr-2
}

.window__form {
    position: relative;
    border: 1px solid #dde1e3;
    height: 42px;
    width: 397px;
    margin-bottom: 5px;
    padding-left: 12px;
    border-radius: 50px;
    background: rgb(255, 255, 255);
    transition: background 0.2s ease 0s;
}

.window__form:focus-within {
    border: 1px solid #737373;
}

.window__form-placeholder {
    position: absolute;
    top: 50%;
    transform: translate(5px, -50%);
    pointer-events: none;
    transition: all 0.14s ease-in-out;
    font-size: 15px;
    color: #adadad;
}

input[type="text"].window__form-input {
    color: rgb(0, 0, 0);
    border: none;
    padding: 5px;
    height: 16px;
    font-size: 14px;
    display: block;
    box-sizing: border-box;
    width: 90%;
    background: rgb(255, 255, 255);
    bottom: 0px;
    appearance: textfield;
    -webkit-rtl-ordering: logical;
    cursor: text;
    letter-spacing: normal;
    word-spacing: normal;
    text-transform: none;
    text-indent: 0px;
    text-shadow: none;
    text-align: start;
    margin-top: 18px;
    transition: background 0.2s ease 0s;
}

input[type="text"].window__form-input:focus {
    outline: none;
}

input[type="text"].window__form-input.c-fix,
input[type="text"].window__form-input:focus,
input[type="text"].window__form-input:not(:placeholder-shown) {
    border-color: transparent;
}

input[type="text"].window__form-input.c-fix~label,
input[type="text"].window__form-input:focus~label,
input[type="text"].window__form-input:not(:placeholder-shown)~label {
    font-size: 10px;
    top: calc(20% - 0.5rem);
    transform: translate(5px, 0%);
    transition: all 0.2s ease 0s;
    z-index: 1;
}

input[type="text"].window__form-input::-webkit-input-placeholder {
    color: transparent;
}

input[type="text"].window__form-input::-moz-placeholder {
    color: transparent;
}

input[type="text"].window__form-input:-ms-input-placeholder {
    color: transparent;
}

input[type="password"].window__form-input {
    color: rgb(0, 0, 0);
    border: none;
    padding: 5px;
    height: 16px;
    font-size: 14px;
    display: block;
    box-sizing: border-box;
    width: 90%;
    background: rgb(255, 255, 255);
    bottom: 0px;
    appearance: textfield;
    -webkit-rtl-ordering: logical;
    cursor: text;
    letter-spacing: normal;
    word-spacing: normal;
    text-transform: none;
    text-indent: 0px;
    text-shadow: none;
    text-align: start;
    margin-top: 18px;
    transition: background 0.2s ease 0s;
}

input[type="password"].window__form-input:focus {
    outline: none;
}

input[type="password"].window__form-input.c-fix,
input[type="password"].window__form-input:focus,
input[type="password"].window__form-input:not(:placeholder-shown) {
    border-color: transparent;
}

input[type="password"].window__form-input.c-fix~label,
input[type="password"].window__form-input:focus~label,
input[type="password"].window__form-input:not(:placeholder-shown)~label {
    font-size: 10px;
    top: calc(20% - 0.5rem);
    transform: translate(5px, 0%);
    transition: all 0.2s ease 0s;
    z-index: 1;
}

input[type="password"].window__form-input::-webkit-input-placeholder {
    color: transparent;
}

input[type="password"].window__form-input::-moz-placeholder {
    color: transparent;
}

input[type="password"].window__form-input:-ms-input-placeholder {
    color: transparent;
}

.window__help-line {
    position: relative;
    z-index: 1;
    overflow: hidden;
    text-align: start;
    padding-left: 22px;
    font-size: smaller;
}

.window__help-line:before,
.window__help-line:after {
    content: '';
    display: inline-block;
    width: 100%;
    height: 2px;
    background: #f3f4f6;
    z-index: -1;
    position: relative;
    vertical-align: middle;
}

.window__help-line:before {
    right: 10px;
    margin: 0 0 0 -100%;
}

.window__help-line:after {
    left: 10px;
    margin: 0 -100% 0 0;
}
</style>