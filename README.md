# Скирпты для обновления информации о товарах сайта tiweworld.ru на маркетплейсах Yandex.market и Ozon #

## seller.py ##

Скрипт отвечает за взаимодействие с маркетплейсом Ozon

1. Получает артикул товаров клиента размещенных на Ozon.
2. Получает список оставшихся товаров с ценами с сайта [timeworld.ru](www.timeworld.ru)
3. Обновляет количество товаров на Ozon из списка оставшихся товаров.
4. Обновляет цены на товары на Ozon из списка оставшихся товаров.

## market.py ##

Скрипт отвечает за взаимодействие с маркетплейсом Yandex.market

1. Получает список оставшихся товаров с ценами с сайта [timeworld.ru](www.timeworld.ru)
2. Получает информацию о товарах клиента, обслуживаемых по модели FBS.
3. Обновляет информацию о количестве товаров (FBS) из списка отсавшихся товаров.
4. Обновляет цену на товары (FBS) из списка оставшихся товаров.
5. Получает инфомарцию о товарах клиента, обслуживаемых по модели DBS
6. Обновляет информацию о количестве товаров (DBS) из списка оставшихся товаров.
7. Обновляет цену на товары (DBS) из списка оставшихся товаров.
