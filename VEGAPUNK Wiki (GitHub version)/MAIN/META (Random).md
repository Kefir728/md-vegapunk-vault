```button
name Создать рандомную заметку
type command
action Templater: Create new note from template
templater true
color black
```


```dataview
table
    title as "Название",
    date as "Дата создания",
    tags as "Теги"
from "My Wiki/_ARCHIVE/Random"
sort date desc