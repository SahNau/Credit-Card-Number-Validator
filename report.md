# **Отчёт о тестировании Credit Card Number Validator**
## Краткое описание
03.03.2021 - 03.03.2021  было проведено функциональное тестирование валидации номеров банковских карт.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Не активируется лицензия приложения при вводе правильного ключа #1](https://github.com/SahNau/KeyValidator/issues/1)
* [Не активируется лицензия приложения при вводе правильного ключа #2](https://github.com/SahNau/KeyValidator/issues/2)
* [Активируется лицензия приложения при вводе ключа, который не должен работать #3](https://github.com/SahNau/KeyValidator/issues/3)

## Описание процесса тестирования
 В процессе тестирования использовались следующие артефакты:

* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)


В качестве тестовых данных использовались данные [номера карт](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* VISA: 4843222494674305 Ответ "Result is OK", карта работает
* VISA: 4485548449630189 Ответ "Result is OK", карта работает
* VISA: 4485703588484852721 Ответ "Result is OK", карта работает
* Discover: 6011103879483341 Ответ "Result is OK", карта работает
* Discover: 6011204208426093625 Ответ "Result is OK", карта работает
* MasterCard: 5446912891133784 Ответ "Result is OK", карта работает
* MasterCard: 5284187089118468 Ответ "Result is OK", карта работает
* MasterCard: 5447770008420901 Ответ "Result is OK", карта работает
* American Express (AMEX): 374525035093495 Ответ "Result is OK", карта работает
* American Express (AMEX): 373825222565664 Ответ "Result is OK", карта работает

Тестирование производилось в следующем окружении:

* Windows 10 x64
* Java 11
* IntelliJ IDEA 2020.3.2