﻿# Представление результатов

| ID | Назначение/название | Сценарий | Ожидаемый результат | Фактический результат | Оценка |
|:---:|:---:|:---|:---|:---|:---|
| 1 | Регистрация нового аккаунта пользователя | 1. Запустите приложение, откроется [стартовое окно](#1) приложения.<br> 2. Нажмите кнопку "Регистрация".<br> 3. В открывшемся [окне](#2) введите адрес электронной почты и пароль.<br>4. Нажмите кнопку "Зарегистрироваться".<br>5. Произошло перенаправление на [окно заполнения](#3) профиля.<br>6. В появившемся окне введите имя пользователя и зугрузите фото пользователя, нажмите кнопку "Зарегистрироваться".| Произошло перенаправление на [главную страницу](#5) приложения. |  Произошло перенаправление на главную страницу приложения.| Тест пройден |
| 2 | Регистрация уже сущестующего аккаунта пользователя | 1. Запустите приложение, откроется [стартовое окно](#1) приложения.<br> 2. Нажмите кнопку "Зарегистрироваться".<br> 3. На открывшейся [странице](#2) введите имя пользователя и пароль, уже сущестующего аккаунта в системе.<br>4. Нажмите кнопку "Зарегистрироваться".| Появилось сообщение с уведомлением о том, что данное имя уже занято. | Функционал не реализован | Тест не пройден |
| 3 | Вход в зарегистрированный аккаунт | 1. Запустите приложение, откроется [стартовое окно](#1) приложения.<br> 2. Нажмите кнопку "Вход".<br> 3. В открывшемся [окне](#4) введите адрес электронной почты и пароль, уже сущестующего аккаунта в системе.<br>4. Нажмите кнопку "Войти".| Произошло перенаправление на [главную страницу](#5) приложения.| Произошло перенаправление на главную страницу приложения. | Тест пройден |
| 4 | Добавление новой поездки | 1. Выполните сценарий 3.<br> 2. Нажмите кнопку "Добавить поездку".<br> 3. На открывшейся [странице](#5) заполните все обязательные поля.<br>4. Нажмите кнопку "Добавить".| Произошло перенаправление на [главную страницу](#5) приложения.| Произошло перенаправление на главную страницу приложения. | Тест пройден |
| 5 | Поиск поездки| 1. Выполните сценарий 3.<br> 2. Нажмите кнопку "Найти поездку".<br> 3. На открывшейся [странице](#6) заполните все обязательные поля.<br>4. Нажмите кнопку "Найти".| Появилось [окно](#7) содержащее список выбранных по критериям поездок. | Появилось окно содержащее список выбранных по критериям поездок. | Тест пройден |
| 6 | Заказ поездки | 1. Выполните сценарий 5.<br> 2. Выберите поездку и нажмите кнопку «Заказать».<br> | Произошло перенаправление на [главную страницу](#5) приложения. | Произошло перенаправление на главную страницу приложения. | Тест пройден |
| 7 | Просмотр поездок пользователя | 1. Выполните сценарий 3.<br>2. Нажмите кнопку «Мои поездки».<br>| Появилось [окно](#8) содержащее список когда-либо добавленных пользователем поездок. | Появилось окно содержащее список когда-либо добавленных пользователем поездок. | Тест пройден |
| 8 | Выход из аккаунта| 1. Выполните сценарий 3.<br>2. Нажмите на кнопку "Выйти".| Произошло перенаправление на [стартовое окно](#1) приложения. | Произошло перенаправление на стартовое окно приложения. | Тест пройден |
| 9 | Вход в незарегистрированный аккаунт| 1. Запустите приложение, откроется [стартовое окно](#1) приложения.<br> 2. Нажмите кнопку "Вход".<br> 3. В открывшемся [окне](#2) введите имя пользователя и пароль, несущестующего аккаунта в системе и нажмите кнопку «Вход». | Появилось сообщение на странице с уведомлением о том, что аккаунт не найден в ситстеме. | Функционал не реализован | Тест не пройден |
| 10 | Переписка с водителем| 1. Выполните сценарий 5.<br>2. Нажмите кнопку "Сообщения". | В открывшемся окне ведётся переписка с водителем. | Функционал не реализован | Тест не пройден |
|  |  |  |  |  |  |

# Иллюстрации

<a name="1"/>

Рисунок 1.
![Рисунок 1](../Images/Testing/1.jpg)

<a name="2"/>

Рисунок 2.
![Рисунок 2](../Images/Testing/2.jpg)

<a name="3"/>

Рисунок 3.
![Рисунок 3](../Images/Testing/3.jpg)

<a name="4"/>

Рисунок 4.
![Рисунок 4](../Images/Testing/4.jpg)

<a name="5"/>

Рисунок 5.
![Рисунок 5](../Images/Testing/5.jpg)

<a name="6"/>

Рисунок 6.
![Рисунок 6](../Images/Testing/6.jpg)

<a name="7"/>

Рисунок 7.
![Рисунок 7](../Images/Testing/7.jpg)

<a name="8"/>

Рисунок 8.
![Рисунок 8](../Images/Testing/8.jpg)

