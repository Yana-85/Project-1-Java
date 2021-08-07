# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

07.08.21 г. - 07.08.21 г. было проведено тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Отображается pезультат "Fail" в консоли после запуска кода (карта American Express)](https://github.com/Yana-85/Project-1-Java/issues/1)
* [Отображается pезультат "Fail" в консоли после запуска кода (карта VISA)](https://github.com/Yana-85/Project-1-Java/issues/2)
* [Отображается pезультат "Fail" в консоли после запуска кода (карта JCB)](https://github.com/Yana-85/Project-1-Java/issues/3)

## Описание процесса тестирования

В качестве тестовых данных использовались данные с сервисов: [getcreditcardnumbers.com](https://www.getcreditcardnumbers.com/) и [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* Карта American Express 371973023492423 - ожидаемый результат "Ok", карта валидна;
* Карта VISA 4556197657252165136 - ожидаемый результат "Ok", карта валидна;
* Карта JCB 3529719870404492533 - ожидаемый результат "Ok", карта валидна.

Тестирование производилось в следующем окружении:
* ОС: Windows 10, версия 21H1, 64-разрядная операционная система
* Java version "11.0.11"
