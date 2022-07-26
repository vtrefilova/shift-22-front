# My-services

## Описание

Приложение для поиска и размещения услуг. На данный момент реализована визуальная часть проекта. Из запросов к backend части реализована регистрация пользователя. 

## Функциональность

На главной странице доступна лента с карточками услуг. При клике на карточку всплывает модальное окно с подробным описанием услуги. Карточки можно фильтровать по названию услуги, городу и дате размещения объявления. Хедер отображается по разному для загегистрированного и незарегистрированного пользователя. В хедере для незаригестрированного пользователя размещены кнопки вход и регистрация при клике на которые всплывает модальное окно с соответствующей формой. В хедере для зарегистрированного пользователя размещены ссылки на странички личного кабинета пользователя и кнопка создать услугу при клике на которую всплывает модальное окно с формой. Чтобы переключаться между версией для зарегистрированного и незарегистрированного пользователя, нужно в файле App.js в массиве value передаваемом провайдеру в поле isLoggedin проставлять значения true и false соответственно. В личном кабинете 3 странички: профиль, мои заказы и мои услуги. В профиле размещена информация о пользователе. На странице мои заказы отображаются карточки заказанных услуг. На странице мои услуги отображаются карточки предложенных услуг. 

## Демо

![](https://github.com/vtrefilova/my-services/blob/master/ScreenShots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-07-21%20%D0%B2%2016.47.11.png)

![](https://github.com/vtrefilova/my-services/blob/master/ScreenShots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-07-21%20%D0%B2%2016.45.59.png)

![](https://github.com/vtrefilova/my-services/blob/master/ScreenShots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-07-21%20%D0%B2%2016.47.40.png)

![](https://github.com/vtrefilova/my-services/blob/master/ScreenShots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-07-21%20%D0%B2%2016.47.58.png)

![](https://github.com/vtrefilova/my-services/blob/master/ScreenShots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-07-21%20%D0%B2%2016.48.15.png)

## Технологии в проекте

## Техническое описание проекта

Приложение создано при помощи Create React App. Были использованы следующие технологии и библиотеки: React, React hooks, react-router-dom, react-bootstrap, styled-components, axios, Aviasales API автокомплита для стран, городов и аэропортов.

## Что нужно для запуска

Чтобы запустить проект нужно склонировать его из git репозитория и выполнить следующие команды:

### `npm install`

установка пакетов необходимых для запуска проекта

### `npm start`

запуск проекта на localhost
