<template>
    <div class="window__page">
        <div class="window">
            <div class="window__img"></div>
            <div class="window__info">
                <div class="window__header">
                    <div class="window__panel">
                        <div class="window__panel-hidden"></div>
                        <div class="window__panel-title">
                            Регистрация
                        </div>
                        <div class="window__panel-close">
                            <div class="window__close-icon">
                                <CloseIcon />
                            </div>
                        </div>
                    </div>
                </div>
                <div class="window__body">
                    <div class="window__body">
                        <div class="window__forms">
                            <div class="window__form">
                                <input class="window__form-input" type="text" placeholder="Имя..." />
                            </div>
                            <div class="window__form">
                                <input type="text" class="window__form-input" placeholder="Фамилия..." />
                            </div>
                            <div class="window__form">
                                <input class="window__form-input" type="password" placeholder="Введите пароль..." />
                            </div>
                            <div class="window__form">
                                <input class="window__form-input" type="password" placeholder="Повторите пароль..." />
                            </div>
                            <div class="window__form">
                                Выберите город:
                                <select name="city" class="window__form-select">
                                    <option value="Москва">Москва</option>
                                    <option value="Санкт-Петербург">Санкт-Петербург</option>
                                    <option value="Пенза">Пенза</option>
                                    <option value="Абакан">Абакан</option>
                                    <option value="Азов">Азов</option>
                                    <option value="Александров">Александров</option>
                                    <option value="Алексин">Алексин</option>
                                    <option value="Альметьевск">Альметьевск</option>
                                    <option value="Анапа">Анапа</option>
                                    <option value="Ангарск">Ангарск</option>
                                    <option value="Анжеро">Анжеро-Судженск</option>
                                    <option value="Апатиты">Апатиты</option>
                                    <option value="Арзамас">Арзамас</option>
                                    <option value="Армавир">Армавир</option>
                                    <option value="Арсеньев">Арсеньев</option>
                                    <option value="Артем">Артем</option>
                                    <option value="Архангельск">Архангельск</option>
                                    <option value="Асбест">Асбест</option>
                                    <option value="Астрахань">Астрахань</option>
                                    <option value="Ачинск">Ачинск</option>
                                    <option value="Балаково">Балаково</option>
                                    <option value="Балахна">Балахна</option>
                                    <option value="Балашиха">Балашиха</option>
                                    <option value="Балашов">Балашов</option>
                                    <option value="Барнаул">Барнаул</option>
                                    <option value="Батайск">Батайск</option>
                                    <option value="Белгород">Белгород</option>
                                    <option value="Белебей">Белебей</option>
                                    <option value="Белово">Белово</option>
                                    <option value="Белогорск (Амурская область)">Белогорск (Амурская область)</option>
                                    <option value="Белорецк">Белорецк</option>
                                    <option value="Белореченск">Белореченск</option>
                                    <option value="Бердск">Бердск</option>
                                    <option value="Березники">Березники</option>
                                    <option value="Березовский (Свердловская область)">Березовский (Свердловская
                                        область)</option>
                                    <option value="Бийск">Бийск</option>
                                    <option value="Биробиджан">Биробиджан</option>
                                    <option value="Благовещенск (Амурская область)">Благовещенск (Амурская область)
                                    </option>
                                    <option value="Бор">Бор</option>
                                    <option value="Борисоглебск">Борисоглебск</option>
                                    <option value="Боровичи">Боровичи</option>
                                    <option value="Братск">Братск</option>
                                    <option value="Брянск">Брянск</option>
                                    <option value="Бугульма">Бугульма</option>
                                    <option value="Буденновск">Буденновск</option>
                                    <option value="Бузулук">Бузулук</option>
                                    <option value="Буйнакск">Буйнакск</option>
                                    <option value="Великие Луки">Великие Луки</option>
                                    <option value="Великий Новгород">Великий Новгород</option>
                                    <option value="Верхняя Пышма">Верхняя Пышма</option>
                                    <option value="Видное">Видное</option>
                                    <option value="Владивосток">Владивосток</option>
                                    <option value="Владикавказ">Владикавказ</option>
                                    <option value="Владимир">Владимир</option>
                                    <option value="Волгоград">Волгоград</option>
                                    <option value="Волгодонск">Волгодонск</option>
                                    <option value="Волжск">Волжск</option>
                                    <option value="Волжский">Волжский</option>
                                    <option value="Вологда">Вологда</option>
                                    <option value="Вольск">Вольск</option>
                                    <option value="Воркута">Воркута</option>
                                    <option value="Воронеж">Воронеж</option>
                                    <option value="Воскресенск">Воскресенск</option>
                                    <option value="Воткинск">Воткинск</option>
                                    <option value="Всеволожск">Всеволожск</option>
                                    <option value="Выборг">Выборг</option>
                                    <option value="Выкса">Выкса</option>
                                    <option value="Вязьма">Вязьма</option>
                                    <option value="Гатчина">Гатчина</option>
                                    <option value="Геленджик">Геленджик</option>
                                    <option value="Георгиевск">Георгиевск</option>
                                    <option value="Глазов">Глазов</option>
                                    <option value="Горно-Алтайск">Горно-Алтайск</option>
                                    <option value="Грозный">Грозный</option>
                                    <option value="Губкин">Губкин</option>
                                    <option value="Гудермес">Гудермес</option>
                                    <option value="Гуково">Гуково</option>
                                    <option value="Гусь-Хрустальный">Гусь-Хрустальный</option>
                                    <option value="Дербент">Дербент</option>
                                    <option value="Дзержинск">Дзержинск</option>
                                    <option value="Димитровград">Димитровград</option>
                                    <option value="Дмитров">Дмитров</option>
                                    <option value="Долгопрудный">Долгопрудный</option>
                                    <option value="Домодедово">Домодедово</option>
                                    <option value="Донской">Донской</option>
                                    <option value="Дубна">Дубна</option>
                                    <option value="Евпатория">Евпатория</option>
                                    <option value="Егорьевск">Егорьевск</option>
                                    <option value="Ейск">Ейск</option>
                                    <option value="Екатеринбург">Екатеринбург</option>
                                    <option value="Елабуга">Елабуга</option>
                                    <option value="Елец">Елец</option>
                                    <option value="Ессентуки">Ессентуки</option>
                                    <option value="Железногорск (Красноярский край)">Железногорск (Красноярский край)
                                    </option>
                                    <option value="Железногорск (Курская область)">Железногорск (Курская область)
                                    </option>
                                    <option value="Жигулевск">Жигулевск</option>
                                    <option value="Жуковский">Жуковский</option>
                                    <option value="Заречный">Заречный</option>
                                    <option value="Зеленогорск">Зеленогорск</option>
                                    <option value="Зеленодольск">Зеленодольск</option>
                                    <option value="Златоуст">Златоуст</option>
                                    <option value="Иваново">Иваново</option>
                                    <option value="Ивантеевка">Ивантеевка</option>
                                    <option value="Ижевск">Ижевск</option>
                                    <option value="Избербаш">Избербаш</option>
                                    <option value="Иркутск">Иркутск</option>
                                    <option value="Искитим">Искитим</option>
                                    <option value="Ишим">Ишим</option>
                                    <option value="Ишимбай">Ишимбай</option>
                                    <option value="Йошкар-Ола">Йошкар-Ола</option>
                                    <option value="Казань">Казань</option>
                                    <option value="Калининград">Калининград</option>
                                    <option value="Калуга">Калуга</option>
                                    <option value="Каменск-Уральский">Каменск-Уральский</option>
                                    <option value="Каменск-Шахтинский">Каменск-Шахтинский</option>
                                    <option value="Камышин">Камышин</option>
                                    <option value="Канск">Канск</option>
                                    <option value="Каспийск">Каспийск</option>
                                    <option value="Кемерово">Кемерово</option>
                                    <option value="Керчь">Керчь</option>
                                    <option value="Кинешма">Кинешма</option>
                                    <option value="Кириши">Кириши</option>
                                    <option value="Киров (Кировская область)">Киров (Кировская область)</option>
                                    <option value="Кирово-Чепецк">Кирово-Чепецк</option>
                                    <option value="Киселевск">Киселевск</option>
                                    <option value="Кисловодск">Кисловодск</option>
                                    <option value="Клин">Клин</option>
                                    <option value="Клинцы">Клинцы</option>
                                    <option value="Ковров">Ковров</option>
                                    <option value="Когалым">Когалым</option>
                                    <option value="Коломна">Коломна</option>
                                    <option value="Комсомольск-на-Амуре">Комсомольск-на-Амуре</option>
                                    <option value="Копейск">Копейск</option>
                                    <option value="Королев">Королев</option>
                                    <option value="Кострома">Кострома</option>
                                    <option value="Котлас">Котлас</option>
                                    <option value="Красногорск">Красногорск</option>
                                    <option value="Краснодар">Краснодар</option>
                                    <option value="Краснокаменск">Краснокаменск</option>
                                    <option value="Краснокамск">Краснокамск</option>
                                    <option value="Краснотурьинск">Краснотурьинск</option>
                                    <option value="Красноярск">Красноярск</option>
                                    <option value="Кропоткин">Кропоткин</option>
                                    <option value="Крымск">Крымск</option>
                                    <option value="Кстово">Кстово</option>
                                    <option value="Кузнецк">Кузнецк</option>
                                    <option value="Кумертау">Кумертау</option>
                                    <option value="Кунгур">Кунгур</option>
                                    <option value="Курган">Курган</option>
                                    <option value="Курск">Курск</option>
                                    <option value="Кызыл">Кызыл</option>
                                    <option value="Лабинск">Лабинск</option>
                                    <option value="Лениногорск">Лениногорск</option>
                                    <option value="Ленинск-Кузнецкий">Ленинск-Кузнецкий</option>
                                    <option value="Лесосибирск">Лесосибирск</option>
                                    <option value="Липецк">Липецк</option>
                                    <option value="Лиски">Лиски</option>
                                    <option value="Лобня">Лобня</option>
                                    <option value="Лысьва">Лысьва</option>
                                    <option value="Лыткарино">Лыткарино</option>
                                    <option value="Люберцы">Люберцы</option>
                                    <option value="Магадан">Магадан</option>
                                    <option value="Магнитогорск">Магнитогорск</option>
                                    <option value="Майкоп">Майкоп</option>
                                    <option value="Махачкала">Махачкала</option>
                                    <option value="Междуреченск">Междуреченск</option>
                                    <option value="Мелеуз">Мелеуз</option>
                                    <option value="Миасс">Миасс</option>
                                    <option value="Минеральные Воды">Минеральные Воды</option>
                                    <option value="Минусинск">Минусинск</option>
                                    <option value="Михайловка">Михайловка</option>
                                    <option value="Михайловск (Ставропольский край)">Михайловск (Ставропольский край)
                                    </option>
                                    <option value="Мичуринск">Мичуринск</option>
                                    <option value="Мурманск">Мурманск</option>
                                    <option value="Муром">Муром</option>
                                    <option value="Мытищи">Мытищи</option>
                                    <option value="Набережные Челны">Набережные Челны</option>
                                    <option value="Назарово">Назарово</option>
                                    <option value="Назрань">Назрань</option>
                                    <option value="Нальчик">Нальчик</option>
                                    <option value="Наро-Фоминск">Наро-Фоминск</option>
                                    <option value="Находка">Находка</option>
                                    <option value="Невинномысск">Невинномысск</option>
                                    <option value="Нерюнгри">Нерюнгри</option>
                                    <option value="Нефтекамск">Нефтекамск</option>
                                    <option value="Нефтеюганск">Нефтеюганск</option>
                                    <option value="Нижневартовск">Нижневартовск</option>
                                    <option value="Нижнекамск">Нижнекамск</option>
                                    <option value="Нижний Новгород">Нижний Новгород</option>
                                    <option value="Нижний Тагил">Нижний Тагил</option>
                                    <option value="Новоалтайск">Новоалтайск</option>
                                    <option value="Новокузнецк">Новокузнецк</option>
                                    <option value="Новокуйбышевск">Новокуйбышевск</option>
                                    <option value="Новомосковск">Новомосковск</option>
                                    <option value="Новороссийск">Новороссийск</option>
                                    <option value="Новосибирск">Новосибирск</option>
                                    <option value="Новотроицк">Новотроицк</option>
                                    <option value="Новоуральск">Новоуральск</option>
                                    <option value="Новочебоксарск">Новочебоксарск</option>
                                    <option value="Новочеркасск">Новочеркасск</option>
                                    <option value="Новошахтинск">Новошахтинск</option>
                                    <option value="Новый Уренгой">Новый Уренгой</option>
                                    <option value="Ногинск">Ногинск</option>
                                    <option value="Норильск">Норильск</option>
                                    <option value="Ноябрьск">Ноябрьск</option>
                                    <option value="Нягань">Нягань</option>
                                    <option value="Обнинск">Обнинск</option>
                                    <option value="Одинцово">Одинцово</option>
                                    <option value="Озерск (Челябинская область)">Озерск (Челябинская область)</option>
                                    <option value="Октябрьский">Октябрьский</option>
                                    <option value="Омск">Омск</option>
                                    <option value="Орел">Орел</option>
                                    <option value="Оренбург">Оренбург</option>
                                    <option value="Орехово-Зуево">Орехово-Зуево</option>
                                    <option value="Орск">Орск</option>
                                    <option value="Павлово">Павлово</option>
                                    <option value="Павловский Посад">Павловский Посад</option>
                                    <option value="Первоуральск">Первоуральск</option>
                                    <option value="Пермь">Пермь</option>
                                    <option value="Петрозаводск">Петрозаводск</option>
                                    <option value="Петропавловск-Камчатский">Петропавловск-Камчатский</option>
                                    <option value="Подольск">Подольск</option>
                                    <option value="Полевской">Полевской</option>
                                    <option value="Прокопьевск">Прокопьевск</option>
                                    <option value="Прохладный">Прохладный</option>
                                    <option value="Псков">Псков</option>
                                    <option value="Пушкино">Пушкино</option>
                                    <option value="Пятигорск">Пятигорск</option>
                                    <option value="Раменское">Раменское</option>
                                    <option value="Ревда">Ревда</option>
                                    <option value="Реутов">Реутов</option>
                                    <option value="Ржев">Ржев</option>
                                    <option value="Рославль">Рославль</option>
                                    <option value="Россошь">Россошь</option>
                                    <option value="Ростов-на-Дону">Ростов-на-Дону</option>
                                    <option value="Рубцовск">Рубцовск</option>
                                    <option value="Рыбинск">Рыбинск</option>
                                    <option value="Рязань">Рязань</option>
                                    <option value="Салават">Салават</option>
                                    <option value="Сальск">Сальск</option>
                                    <option value="Самара">Самара</option>
                                    <option value="Саранск">Саранск</option>
                                    <option value="Сарапул">Сарапул</option>
                                    <option value="Саратов">Саратов</option>
                                    <option value="Саров">Саров</option>
                                    <option value="Свободный">Свободный</option>
                                    <option value="Севастополь">Севастополь</option>
                                    <option value="Северодвинск">Северодвинск</option>
                                    <option value="Северск">Северск</option>
                                    <option value="Сергиев Посад">Сергиев Посад</option>
                                    <option value="Серов">Серов</option>
                                    <option value="Серпухов">Серпухов</option>
                                    <option value="Сертолово">Сертолово</option>
                                    <option value="Сибай">Сибай</option>
                                    <option value="Симферополь">Симферополь</option>
                                    <option value="Славянск-на-Кубани">Славянск-на-Кубани</option>
                                    <option value="Смоленск">Смоленск</option>
                                    <option value="Соликамск">Соликамск</option>
                                    <option value="Солнечногорск">Солнечногорск</option>
                                    <option value="Сосновый Бор">Сосновый Бор</option>
                                    <option value="Сочи">Сочи</option>
                                    <option value="Ставрополь">Ставрополь</option>
                                    <option value="Старый Оскол">Старый Оскол</option>
                                    <option value="Стерлитамак">Стерлитамак</option>
                                    <option value="Ступино">Ступино</option>
                                    <option value="Сургут">Сургут</option>
                                    <option value="Сызрань">Сызрань</option>
                                    <option value="Сыктывкар">Сыктывкар</option>
                                    <option value="Таганрог">Таганрог</option>
                                    <option value="Тамбов">Тамбов</option>
                                    <option value="Тверь">Тверь</option>
                                    <option value="Тимашевск">Тимашевск</option>
                                    <option value="Тимашевск">Тихвин</option>
                                    <option value="Тихорецк">Тихорецк</option>
                                    <option value="Тобольск">Тобольск</option>
                                    <option value="Тольятти">Тольятти</option>
                                    <option value="Томск">Томск</option>
                                    <option value="Троицк">Троицк</option>
                                    <option value="Туапсе">Туапсе</option>
                                    <option value="Туймазы">Туймазы</option>
                                    <option value="Тула">Тула</option>
                                    <option value="Тюмень">Тюмень</option>
                                    <option value="Узловая">Узловая</option>
                                    <option value="Улан-Удэ">Улан-Удэ</option>
                                    <option value="Ульяновск">Ульяновск</option>
                                    <option value="Урус-Мартан">Урус-Мартан</option>
                                    <option value="Усолье-Сибирское">Усолье-Сибирское</option>
                                    <option value="Уссурийск">Уссурийск</option>
                                    <option value="Усть-Илимск">Усть-Илимск</option>
                                    <option value="Уфа">Уфа</option>
                                    <option value="Ухта">Ухта</option>
                                    <option value="Феодосия">Феодосия</option>
                                    <option value="Фрязино">Фрязино</option>
                                    <option value="Хабаровск">Хабаровск</option>
                                    <option value="Ханты-Мансийск">Ханты-Мансийск</option>
                                    <option value="Хасавюрт">Хасавюрт</option>
                                    <option value="Химки">Химки</option>
                                    <option value="Чайковский">Чайковский</option>
                                    <option value="Чапаевск">Чапаевск</option>
                                    <option value="Чебоксары">Чебоксары</option>
                                    <option value="Челябинск">Челябинск</option>
                                    <option value="Черемхово">Черемхово</option>
                                    <option value="Череповец">Череповец</option>
                                    <option value="Черкесск">Черкесск</option>
                                    <option value="Черногорск">Черногорск</option>
                                    <option value="Чехов">Чехов</option>
                                    <option value="Чистополь">Чистополь</option>
                                    <option value="Чита">Чита</option>
                                    <option value="Шадринск">Шадринск</option>
                                    <option value="Шали">Шали</option>
                                    <option value="Шахты">Шахты</option>
                                    <option value="Шуя">Шуя</option>
                                    <option value="Щекино">Щекино</option>
                                    <option value="Щелково">Щелково</option>
                                    <option value="Электросталь">Электросталь</option>
                                    <option value="Элиста">Элиста</option>
                                    <option value="Энгельс">Энгельс</option>
                                    <option value="Южно-Сахалинск">Южно-Сахалинск</option>
                                    <option value="Юрга">Юрга</option>
                                    <option value="Якутск">Якутск</option>
                                    <option value="Ялта">Ялта</option>
                                    <option value="Ярославль">Ярославль</option>
                                </select>
                            </div>
                            <div class="window__gender">
                                Ваш пол:
                                <div class="window__gender-container">
                                    <div class="window__radio-container">
                                        <input class="window__radio" type="radio" name="sex" /> Женский
                                    </div>
                                    <div class="window__radio-container">
                                        <input class="window__radio" type="radio" name="sex" />
                                        Мужской
                                    </div>
                                </div>
                            </div>
                            <div class="window__agreement">
                                <div class="window__agreement-container">
                                    <input type="checkbox" />
                                    <div>Нажимая кнопку "Зарегестрироваться", я
                                        подтверждаю свою
                                        деепспособность, согласие на получение информации об оформлении и получении
                                        заказа</div>
                                </div>
                                <div class="window__agreement-container">
                                    <input type="checkbox" />
                                    <div>Я подтверждаю свое
                                        согласие на обработку персональных данных</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="window__footer">
                        Зарегестрироваться
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
import CloseIcon from "./icones/CloseIcon.vue"

export default {
    components: { OdnoklassnikiIcon, VkIcon, TwitterIcon, CloseIcon }
}
</script>
  
<style scoped>
.window {
    @apply justify-between rounded rounded-lg container mt-10 mb-10 text-sm bg-gray-300 text-dark-300 h-2xl w-4xl flex flex-row border-gray-300 border
}

.window__info {
    @apply flex flex-col w-full pl-10 pr-10
}

.window__img {
    background-image: url("../../public/photos/registration/photo.jpg");
    max-width: 80%;
    min-width: 40%;
    height: auto;
    background-size: cover;
}

.window__img {
    @apply text-4xl
}

.window__img {
    @apply rounded rounded-lg rounded-r-none
}

.window__header {
    @apply
}

.window__body {
    @apply pl-5 pr-5
}

.window__panel {
    @apply border border-b-blue-800 pt-5 border-2 border-t-0 border-l-0 border-r-0 flex flex-row justify-between
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
    @apply flex flex-col gap-4 gap-y-4 items-center justify-center w-full
}

.window__radio-container {
    @apply w-full flex flex-row items-center justify-center gap-2 cursor-default
}

.window__radio {
    @apply w-full px-2 py-1
}

.window__form {
    @apply w-full
}

.window__gender {
    @apply w-full items-start justify-start flex flex-col gap-2
}

.window__gender-container {
    @apply flex flex-row gap-2
}

.window__agreement-container {
    @apply flex items-start gap-2 justify-start text-xs text-gray-500
}

.window__form-input {
    @apply w-full px-2 py-1 bg-transparent border-l-transparent border-r-transparent border-t-transparent border-b-gray-400 border-2 outline-none ring-0 hover: (outline-none ring-0)
}

.window__form-select {
    @apply w-full px-2 py-1 bg-transparent border-l-transparent border-r-transparent border-t-transparent border-b-gray-400 border-2 outline-none ring-0 hover: (outline-none ring-0)
}

.window__footer {
    @apply mt-4 py-2 px-5 bg-blue-700 text-white cursor-pointer hover: (bg-blue-600) active:(bg-blue-800) w-44 text-center
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
</style>