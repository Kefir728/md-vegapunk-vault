---
title: Список книг
tags:
  - list
---
```button
name Создать обзор
type command
action Templater: Create new note from template
templater true
color red
```
# Список книг

В этой заметке собраны все книги, которые я прочитал, с краткими заметками о них. Используйте эту заметку для быстрого доступа к информации о ваших книгах.

## Таблица книг

```dataview
table
    title as "Название книги",
    author as "Автор",
    genre as "Жанр",
    rating as "Оценка",
    date-read as "Дата чтения",
    pages as "Количество страниц",
    tags as "Теги"
from #books and "My Wiki/ENTERTAINMENT/BOOKS AND ARTICLES"
sort date-read desc
