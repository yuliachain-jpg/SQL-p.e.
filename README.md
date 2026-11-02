# SQL Practice (PostgreSQL)

Учебные задачи по SQL.

## Темы
SELECT, WHERE, JOIN, GROUP BY, COUNT, SUM, агрегатные функции

## Структура
папки  по темам

## Пример
-- Количество заказов по клиентам
SELECT customer_id, COUNT(*) 
FROM orders
GROUP BY customer_id;

## Источник задач
Курс «Интерактивный тренажёр по SQL», Stepik

## Статус
Проект пополняется.# SQL-p.e.