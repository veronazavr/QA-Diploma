# Отчёт по итогам автоматизации

## Запланировано/Сделано
Было запланировано:
1. Автоматизировать позитивные и негативные сценарии тестирования работы сервиса для способов покупки через карту и через кредит.
1. Протестировать поля форм.
1. Протестировать поддержку СУБД MySQL и PostgreSQL.

Сделаны всё запланированные тесты. За исключением тестов с БД PostgreSQL из-за отсутствия поддержки приложением этой БД.
Были использованы все инструменты кроме Appveyor, т.к. поддержка CI не была реализована в данном случае.

## Сработавшие риски
1. Сложности с подключением БД.
1. Отсутствовали уникальные css-селекторы.

Главной проблемой стало отсутствие заявленной поддержки PostgreSQL, из-за проверки которой было потрачено много времени.

## Общий итог по времени
1. Планирование автоматизации тестирования - 6-8 часов / факт 7 часов
1. Написание кода тестов - 50-70 часов / факт 64 часа
1. Подготовка отчётных документов по итогам автоматизированного тестирования - 10-16 часов / факт 4 часа
1. Подготовка отчётных документов по итогам автоматизации - 6-8 часов / факт 4 часа

Подготовка тестовой документации оказалась проще, чем изнечально планировалось.
В целом, фактически затраченное время оказалось близким к прогнозному.