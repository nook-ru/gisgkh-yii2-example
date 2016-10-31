# Пример приложения с модулем [opengkh/yii2-gisgkh](https://github.com/opengkh/yii2-gisgkh)

Приложение создано на базе шаблона [Yii 2 Basic Project Template](https://github.com/yiisoft/yii2-app-basic).

В приложении:
 
- подключен модуль `opengkh/yii2-gisgkh`
- реализованы некоторые операции для демонстрации работы модуля

Описание демо-приложения [тут](/app/readme.md)  

Инструкция по подключению и использованию модуля [тут](https://github.com/opengkh/yii2-gisgkh/blob/master/README.md).

Для корректной работы приложения потребуется:
 
- наличие библиотеки `OpenSSL` с поддержкой алгоритмов ГОСТ
- наличие библиотеки `CUrl` версии не ниже `7.45`
- PHP 5.4 и выше

Рабочее окружение можно получить с использованием [образа Docker](/docker/readme.md). 
В рамках примера поставляется набор скриптов для автоматического разоварачивания докера.
