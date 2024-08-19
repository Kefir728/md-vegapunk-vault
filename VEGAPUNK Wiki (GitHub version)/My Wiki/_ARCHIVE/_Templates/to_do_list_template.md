---
date: <% tp.file.creation_date("DD MMMM YYYY") %>
priority: 
due date: 
tags:
  - todo
---
<% await tp.file.move("/My Wiki/_ARCHIVE/ToDo box/" + (await tp.system.prompt("Enter the name for the new page"))) %>

## Описание

{{description}} 

## Задачи
- [ ] {{task_1}}  # Описание первой задачи
- [ ] {{task_2}}  # Описание второй задачи
- [ ] {{task_3}}  # Описание третьей задачи


## Примечания

- **Важно:** 
  - {{important_notes}}  
- **Контактные лица:** 
  - {{contacts}}  
- **Ресурсы:** 
  - {{resources}}  

## Шаги по выполнению

1. {{step_1}}  # Первый шаг к выполнению задачи
2. {{step_2}}  # Второй шаг
3. {{step_3}}  # Третий шаг

## Дополнительные заметки

- {{additional_notes}}  # Любые дополнительные мысли или информация

---

[[ALL TO-DO|Список всех задач]]
