# Stocks
### Задача
Необходимо создать мобильное приложение для мониторинга цен акций на бирже со следующей минимальной функциональностью:
* На стартовом экране отображается список акций. У каждой акции указан тикер, название компании, текущая цена и изменение цены за сутки.
* Пользователь может добавлять акции в избранные и отдельно просматривать этот список.
* Пользователь может искать акции по тикеру или названию и добавлять их в избранные.

Изначальный список тикеров можно взять из трендовых акций (если такая возможность есть в API) или из популярных индексов (например, S&P 500 или Dow Jones). Язык реализации — Swift. В качестве API используйте любые открытые сервисы, которые позволяют решить задачу (советуем сначала узнать про их возможности и ограничения). Можно взять несколько сервисов. Мы рекомендуем Finhub и/или MBOUM, но допустимы и другие.