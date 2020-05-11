# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11.05.2020 - 11.05.2020 было проведено тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 0.3

В результате тестирования выявлены следующие дефекты:
* Действующая кредитная карта VISA, имеющая больше 16 цифр, не проходит проверку

VISA:
* 4556391833680674 Result is OK
* 4916986915010313 Result is OK
* 4539489919817515855 Result is FAIL

MasterCard:
* 2221009944462811 Result is OK
* 5303648684620098 Result is OK
* 5507909400392162 Result is OK

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Github
* IntelliJ IDEA

В качестве тестовых данных использовались данные кредитных карт систем VISA и MasterCard

VISA:
* 4556391833680674
* 4916986915010313
* 4539489919817515855

MasterCard:
* 2221009944462811
* 5303648684620098
* 5507909400392162

Тестирование производилось в следующем окружении:
* Windows_NT x64
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)
* Virtual Studio Code Version: 1.45.0 (user setup)
* Chrome: 78.0.3904.130
* IntelliJ IDEA 2020.1.1
