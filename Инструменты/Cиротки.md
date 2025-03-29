---
aliases:
  - Сироты
  - Сиротки
  - Без ссылок
tags:
  - 🧰
  - статус/🌳
---

Заметки у которых нет ссылок.
> [!Map]- **Заметки-сироты**
>
> ```dataview
> list
> from ""
> where length(file.inlinks) =0 and length(file.outlinks) = 0 AND !contains(file.path, "Шаблоны") AND !contains(file.path, "Точка входа")
> ```