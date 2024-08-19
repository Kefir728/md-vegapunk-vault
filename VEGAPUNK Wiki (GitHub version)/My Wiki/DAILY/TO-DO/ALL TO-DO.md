---
tags:
  - list
---
```button
name Создать To-Do List
type command
action Templater: Create new note from template
templater true
color yellow
```
 

# Список незаконченных дел
```dataview
LIST from #in_progress  and "My Wiki/_ARCHIVE/ToDo box"

sort file.ctime DESC
```

 **$\quad$**
## Список законченных дел
```dataview
LIST from #done and "My Wiki/_ARCHIVE/ToDo box"

sort file.ctime DESC
```