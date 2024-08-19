---
title: Список игр
tags:
  - list
---
```button
name Создать обзор
type command
action Templater: Create new note from template
templater true
color purple
```

# Список игр

В этом списке собраны все игры, в которые я играл, с краткими заметками о них. Используйте эту заметку для быстрого доступа к информации о ваших играх.

## Таблица игр

```dataview
table
    title as "Название игры",
    developer as "Разработчик",
    rating as "Оценка",
    complete-date as "Дата игры",
    genre as "Жанр",
    platform as "Платформа",
    tags as "Теги"
from #games and "My Wiki/ENTERTAINMENT/GAMES"

sort rating desc
