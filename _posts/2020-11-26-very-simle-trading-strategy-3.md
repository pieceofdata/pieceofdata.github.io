---
title: Самая простая стратегия для трейдинга — комиссии
tags: проверкаидеи
---

Напомню, что тут происходит.
1. [Рассмотрел очень простую стратегию: покупай после закрытия вниз и продавай после закрытия вверх](https://zenoftrading.github.io/very-simle-trading-strategy-1.html)
2. [Посмотрел сколько может быть закрытий подряд и на что это влияет](https://zenoftrading.github.io/very-simle-trading-strategy-2.html)

Сегодня добрался посмотреть как влияют комиссии.

Буду тестировать для комиссии 0,06%. То есть покупаем акции — минус 0,06%, продаём акции — минус 0,06%. На круг получается 0,12% Понятно, что в реальности может быть меньше, если оборот больше. Но я лучше заложу комиссию побольше.

С виду кажется что там эти 0,06%. Ерунда, даже не заметишь. А по факту очень даже заметишь. Давайте посмотрим.

## Покупки

![Покупки](/assets/images/2020/11/equity_buy_1_5_days_commission.png)

Графики покупок

Слева без комиссий, справа с комиссиями. Как и ожидалось, самый частоторгуемый вариант стремится к 0. Напомню сколько сделок в каждом варианте:
- Equity_Buy_1_Days    1291
- Equity_Buy_2_Days     626
- Equity_Buy_3_Days     294
- Equity_Buy_4_Days     142
- Equity_Buy_5_Days      69

Но что радует, вариант с четырмя закрытиями подряд по прежнему прибыльный. Пусть и меньше, чем в предыдущем рассчёте. Неубыточные последние три варианта.

## Продажи

![Продажи](/assets/images/2020/11/equity_sell_1_5_days_commission.png)

Графики продаж

Количество сделок:
- Equity_Sell_1_Days    1212
- Equity_Sell_2_Days     547
- Equity_Sell_3_Days     238
- Equity_Sell_4_Days      91
- Equity_Sell_5_Days      33

Тут похожая картина, неубыточные последние три варианта.

## Покупки и продажи вместе

![Покупки и продажи вместе](/assets/images/2020/11/equity_buysell_1_5_days_commission.png)

Покупки и продажи вместе

Количество сделок:
- Equity_Buysell_1_Days    2503
- Equity_Buysell_2_Days    1173
- Equity_Buysell_3_Days     532
- Equity_Buysell_4_Days     233
- Equity_Buysell_5_Days     102

Если совершать сделки после каждого закрытия, то примерно в 2018 году у нас не будет депозита. Если дожидаться трёх закрытий подряд, то через 10 лет останемся при своих. Ну и если ждать четы закрытия подряд, то увеличим депозит чуть более, чем в два раза к концу срока.

## И что?

Что с комиссиями:
1. Если ждать 4 закрытия подряд, то за 10 лет будет 233 сделки. Это 23 сделки в год. Это 2 сделки в месяц. На дистанции в 10 лет и комиссии в 0,06% общая доходность стратегии падает на 25%... А ведь есть ещё вариант комиссии 0,3%. Пожалуй стоит прикупить акции московской биржи в долгосрок. Есть ещё вариант, что я что-то напутал в рассчётах. Поправьте меня, если я не прав.
2. Чем больше сделок, тем больше комиссия. В идеале нужно количество сделок минимизировать, а доход в каждой сделке увеличивать.

Что вообще с идеей? Пока понятно, что как-то работает на сбербанке. Что ещё посмотрю:
- Проверю как эта идея ведёт себя на разных классах активов на разных рынках. В комментариях просили добавить ещё пару российских акций. Будет понятно это локальная сбербанковская стратегия или нет.
- Посмотрим как ещё это всё можно улучшить. В комментариях написали пару вариантов для проверки. Ну и у меня вариантов с каждой статьей появляется всё больше.

Как я считал комиссии можно найти в телеграме [https://t.me/zenoftrading](https://t.me/zenoftrading)