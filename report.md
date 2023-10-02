# Отчёт о тестировании _Precision_

## Краткое описание

02.10.23 - 02.10.23 было проведено функциональное тестирование приложения _Precision_.

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:
* Issues ["Не указана точность округления, при расчете дополнительного бонуса новым клиентам"](https://github.com/Tamara756/precision/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Тестовое задание [Задча №2 - Precision](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---precision)

В качестве тестовых данных использовались данные указанные [коде](https://github.com/netology-code/javaqa-homeworks/tree/master/programming#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---precision):
* Заданные переменные: `regularBonus = 0.3` и `specialBonus = 0.6`, ожидаемый результат в переменной `totalBonus`: 0.9 . 

Тестирование производилось в следующем окружении:
* Ubuntu 22.04 LTS amd64
* openjdk 11.0.14.1
* IntelliJ IDEA 2022.2.5 (Community Edition)