# СБЕР СТРАХОВАНИЕ


### XPath


***XPath (XML Path Language)*** — это язык запросов к элементам XML-документа.

https://online.sber.insure/store/propertyins/

#### Страница - "Выбор полиса":

##### Кнопки.

***Квартира*** 

//button[@id="mat-button-toggle-1-button"]

Сдается в аренду - Да

//*[@id="mat-button-toggle-166-button"]

Сдается в аренду - Нет

//*[@id="mat-button-toggle-176-button"]

Расположена на первом или последнем этаже - Да

//*[@id="mat-button-toggle-115-button"]

Расположена на первом или последнем этаже - Нет

//*[@id="mat-button-toggle-125-button"]

***Установлена охранная сигнализация - Да***

//*[@id="mat-button-toggle-136-button"]/span

***Установлена охранная сигнализация - Нет***

//*[@id="mat-button-toggle-146-button"]/span

***Дом*** 

//button[@id="mat-button-toggle-2-button"]

***Сдается в аренду - Да*** 

//*[@id="mat-button-toggle-76-button"]

***Сдается в аренду - Нет***

//*[@id="mat-button-toggle-86-button"]

***Установлена охранная сигнализация - Да***

//*[@id="mat-button-toggle-205-button"]

***Установлена охранная сигнализация - Нет***

//*[@id="mat-button-toggle-215-button"]

***Материал несущих стен - кирпич или монолит***

//*[@id="mat-button-toggle-226-button"]/span

***Материал несущих стен - дерево***

//*[@id="mat-button-toggle-236-button"]/span

***Применить ( Промокод)***

//button[@class="mat-focus-indicator action-back mat-stroked-button mat-button-base"]

***Оформить***

//button[@class="mat-focus-indicator mat-stroced-button mat-button-base mat-accent mat-button-disabled"]

##### Поля для ввода текста

***Регион проживания***

//input[@id="mat-input-0"]

***Срок действия страхования (датапикер)***

//input[@id="mat-input-1"]

***Страховая сумма и объекты страхования (слайдер)***

//*[@id="mat-input-3"]

***Промокод***

//*[@id="mat-input-2"]

##### Каждого чекбокса

##### Каждого датапикера
Дата начала

//mat-datepicker-toggle[@class="mat-datepicker-toggle ng-tns-c61-22"]

##### Логотипа "СБЕР СТРАХОВАНИЕ"

//*[@id="header"]/div/div

##### Слайдера в блоке выбора суммы

//div[class@="mat-slider-wrapper"]

##### Что будет застраховано?(хедер)

//div[@class="sbi-form_row ng-star-inserted"]/div[2]

***Текстовые блоки***
Мебель , техника и ваши вещи

//div[text()[contains(.,"Мебель , техника и ваши вещи")]]

Падение летательных аппаратов и их частей

//div[text()[contains(.,"Падение летательных аппаратов и их частей")]]

##### "Страховая защита включенная в программу" (Каждой колонки в списке, который находится под хедером)

***Левый блок***

//div[text()="Чрезвычайная ситуация"]/ancestor::ul

***Правый блок***

//div[text()="Стихийные бедствия"]/ancestor::ul


#### Страница "Оформление"

##### Кнопки.

***Заполнить по Сбер ID.***

//button[@class="mat-focus-indicator sber-id-button mat-flat-button mat-button-base mat-primary"]

***Мужской***

//*[@id="mat-button-toggle-58-button"]

***Женский***

//*[@id="mat-button-toggle-59-button"]

***Вернуться***

//button[@class="mat-focus-indicator action-back mat-stroked-button mat-button-base"]

***Оформить***

//button[@class="mat-focus-indicator mat-flat-button mat-button-base mat-accent"]


##### Поля для ввода текста

Фамилия

//*[@id="mat-input-4"]

Имя

//*[@id="mat-input-5"]

Отчество

//*[@id="mat-input-6"]

Дата рождения (датапикер)

//*[@id="mat-input-7"]

Серия 

//*[@id="mat-input-8"]

Номер

//*[@id="mat-input-9"]

Дата выдачи (датапикер)

//*[@id="mat-input-10"]

Кем выдан

//*[@id="mat-input-11"]

Код подразделения

//*[@id="mat-input-12"]

Город или населенный пункт

//*[@id="mat-input-14"]

Улица

//*[@id="mat-input-15"]

Дом,литера,корпус,строение

//*[@id="mat-input-16"]

Квартира

//*[@id="mat-input-17"]

Телефон

//*[@id="mat-input-18"]

Электронная почта

//*[@id="mat-input-19"]

Повтор электронной почты

//*[@id="mat-input-20"]


#### Чекбоксы

Отчество отсутствует

//input[@id="mat-checkbox-1"]/label/div

Улица отсутствует

//input[@id="mat-checkbox-2"]/label/div

#### Датапикеры

Дата рождения

//mat-datepicker-toggle[@class="mat-datepicker-toggle ng-tns-c-7"]

Дата выдачи

//mat-datepicker-toggle[@class="mat-datepicker-toggle ng-tns-c-10"]

