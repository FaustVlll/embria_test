# embria test

Вам поступила задача:

Необходимо создать общую ленту новостей для пользователей с возможностью оценки постов в ленте.

Лента должна иметь фильтр по категориям. Любой пользователь может поставить "лайк" или отменить его. Необходимо предусмотреть возможность просмотра списка всех оценивших пост пользователей. Ограничение на размер хранения контента одного поста - 243 байта.

Предложите структуру базы данных MySQL, позволяющую реализовать данную задачу. Напишите базовый модуль на PHP, реализующий функции вывода новостей, добавление нового поста в ленту, установку и отмену "лайка" на новости.

# Описание

Я решил реализовать это задание через api

index.php - точка входа для API запросов

index.html - точка входа для пользовательского интерфейса

Основная логика реализована в классе class/Controller.php

# Установка

Дамп базы - https://github.com/FaustVlll/embria_test/blob/master/test.sql

В файле index.php заменить переменные

$db_name = 'NAME OF DB';

$db_user = 'DB USERNAME';

$db_password = 'DB PASSWORD';

Доступ по адресу http://you_server/index.html

