---
title: Простой бот для крипто биржи Deribit
tags: python deribit api
---
Нашёл тестовое задание на разработчика в один фонд. Само [задание можно посмотреть в файле](https://github.com/zenoftrading/zenoftrading.github.io/blob/master/assets/images/2021/03/algalon_developer_test_ru.pdf). Нужно написать робота для крипто биржи Deribit. Из требований:
1. Написать на python 3
2. Нужно использовать asyncio так как API Deribit работает через websockets
3. Для управления зависимостями использовать poetry
4. Запуск робота через docker и docker compose
5. Написать пару тройку юнит тестов
6. Данные по сделкам сохранять в mysql базу данных.

Не долго думая решил его закодить, потренироваться лишний раз в программировании, заодно разобраться в API Deribit. 

Базу данных использовал sqlite. Юнит тесты пока не делал.

Бот можно использовать как пример работы с API Deribit. Код работает как есть без всяких гарантий.

Ссылку на гитхаб можно найти у меня в телеграме [https://t.me/zenoftrading](https://t.me/zenoftrading/68).
