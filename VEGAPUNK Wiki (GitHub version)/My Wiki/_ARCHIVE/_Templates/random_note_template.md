---
title: <% tp.file.title %>
date: <% tp.file.creation_date("DD MMMM YYYY") %>
tags:
  - meta
---
<% await tp.file.move("/My Wiki/_ARCHIVE/Random/" + (await tp.system.prompt("Enter the name for the new page"))) %>

### Возможные ссылки: 

# Заметка
-