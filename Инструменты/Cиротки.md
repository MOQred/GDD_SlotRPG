---
aliases:
  - Сироты
  - Сиротки
  - Без ссылок
tags:
  - статус/🌳
  - раздел/🧰
---

Заметки у которых нет ссылок.
> [!Map]- **Заметки-сироты**
>
> ```dataview
> list
> from ""
> where length(file.inlinks) =0 and length(file.outlinks) = 0 AND !contains(file.path, "Шаблоны") AND !contains(file.path, "Точка входа") AND !contains(file.path, "README") AND !contains(file.path, "Архив")
> ```

---

Заметки у которых не проставлены теги.
> [!Map]- **Заметки-не крещённые**
> ```dataview
> list
> from ""
> where !contains(file.tags, "#") AND !contains(file.path, "README") AND !contains(file.path, "Архив")
>   ```
 