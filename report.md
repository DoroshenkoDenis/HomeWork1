# Отчёт о тестировании KeyValidator

## Краткое описание

04.03.2021 - 04.03.2021 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 0.1 часа

В результате тестирования выявлены следующие дефекты:
* [Валидный ключ не проходит проверку](https://github.com/DoroshenkoDenis/HomeWork1/issues/1)
* [Не валидный ключ проходит проверку](https://github.com/DoroshenkoDenis/HomeWork1/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Домашнее задание 1 к лекции Введение в Java: JDK, JRE, JVM, IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* [KeyValidator.class](artifacts/KeyValidator.class)


В качестве тестовых данных использовались данные <указать источник, откуда брались тестовые данные>:

Валидные ключи c ожидаемым результатом:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
* b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

Невалидные ключи c ожидаемым результатом:
* 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL

Тестирование производилось в следующем окружении:
* Windows 10 x64
* версия Java 11.0.10
* IntelliJ IDEA 2020.3.2 x64