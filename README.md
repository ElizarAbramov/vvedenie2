# Отчёт о тестировании Credit Card Number Validator


<28.09.2021> - <28.09.2021> было проведено санитарное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:
* [19-ти значный номер карты VISA не проходит проверку](https://github.com/ElizarAbramov/vvedenie2/issues/1)
* [15-ти значный номер карты AMEX не проходит проверку](https://github.com/ElizarAbramov/vvedenie2/issues/2)

В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* 4929263682741446549 VISA, проверка пройдена 
* 341896370218751 AMEX, проверка пройдена
* 5219934339362614 MasterCard, проверка пройдена

Тестирование производилось в следующем окружении:
* Windows 10 Pro; Сборка ОС 19043.1237 х64
* версия Java 11.0.11
* Среда разработки: IntelliJ IDEA 2021.2.1
