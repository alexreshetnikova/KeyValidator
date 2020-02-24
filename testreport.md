# Отчёт о тестировании KeyValidator

## Краткое описание

24/02/2020 - 24/02/2020 было проведено ручное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* https://github.com/alexreshetnikova/KeyValidator/issues/1
* https://github.com/alexreshetnikova/KeyValidator/issues/2
* https://github.com/alexreshetnikova/KeyValidator/issues/3

## Описание процесса тестирования

План тестирования:
1. Установить OpenJDK11.
2. Запустить приложение KeyValidator.
3. Осуществить проверку работы приложения KeyValidator.

Необходимо проверить, что: 
1. Инструкция по установке OpenJDK11 работает под используемую ОС.
2. Приложение запускается и совместимо с Java 11.
3. Приложение работает согласно руководству использования.

В процессе тестирования использовались следующие артефакты:
* Инструкция по установке OpenJDK11
* Руководство использования KeyValidator

В качестве тестовых данных использовались данные, расположенные в "Руководство использования KeyValidator":
Валидные ключи:
8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
80b427f8-92cd-3aae-ba04-3927fbe17c6
b295bc63-9f03-3b4b-af80-969b39f8c262
387eedc6-12e9-3b32-9881-63b6b5e85317
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
Невалидные ключи:
18252235-78e0-44a5-8720-556f0c7da17a
e66075b6-ddad-445e-baf6-161b3289522b
b6d53250-f07e-4352-a293-6102ddf7f1ca
c2bc778a-1cb9-46c6-b435-0489649d2a42
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:
Windows 10 Pro, x64
openjdk version "11.0.6" 2020-01-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
