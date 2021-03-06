# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

07.05.2021-07.05.2021 было проведено функциональное тестирование  приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Some card validation failed](https://github.com/aidthebest/java-1.1/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Описание ДЗ ([ссылка](https://github.com/netology-code/javaqa-homeworks/tree/master/intro))

В качестве тестовых данных использовались [Источник 1](https://www.freeformatter.com/credit-card-number-generator-validator.html), [Источник 2](https://creditcardgenerator.in/bulk-credit-card-generator) и изначально невалидные данные:
* 5351719427810741 - Валидация пройдена успешно 
* VISA 4024007124700278 - Валидация пройдена успешно 
* VISA 4539500929342012406 - Валидация пройдена успешно 
* MasterCard 2720997655592204 - Валидация пройдена успешно 
* Maestro 5893323714841397 - Валидация пройдена успешно 
* JCB 3538270816863306 - Валидация пройдена успешно 
* Diners Club 36038888024591 - Валидация пройдена успешно 
* Diners Club 5337832119058963 - Валидация пройдена успешно 
* MIR 2204194071150478 - Валидация пройдена успешно 
* American Express 343605835149362 - Валидация пройдена успешно 
*

*
* 5984564654846 - Валидация не пройдена
* d34fddf4try67ujg - Валидация не пройдена
* 12343242342342342342342345546456 - Валидация не пройдена

Тестирование производилось в следующем окружении:
* Ubuntu 20.04.2 LTS 64-bit
* версия Java - 11.0.11
