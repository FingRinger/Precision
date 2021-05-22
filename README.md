# Отчет о тестировании приложения Duck Store

## Краткое описание

22.05.2021 - 22.05.2021 бло проведено функциональное тестирование приложения Duck Store
На тестирование затрачено 0,5 часа

В результате тестирования были выявляены следующие дефекты:
* [Некорректный вывод итогового значения переменной totalBonus](https://github.com/FingRinger/Precision/issues/1#issue-898837106)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Баг-репорт
* Отчет о тестировании

В качестве тестовых данных использовались данные Задачи №2 домашнего задания к лекции "Программирование на Java: переменные, операторы, работа с отладчиком":
```java
double regularBonus = 0.3;
double specialBonus = 0.6;
double totalBonus = regularBonus + specialBonus
```
Тестирование производилось в следующем окружении: 
* ОС: Windows 10, x64
* версия Java: openjdk version "11.0.11" 2021-04-20