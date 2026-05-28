---
type: task
status: 1-open
created: 2026-05-28
field: forest-framework
---

# 02 — Bootstrap vault

Создать корневые файлы и папки FOREST в vault пользователя.

## Шаги

1. Скопируй `forest-framework/CLAUDE.md` в `<vault-root>/CLAUDE.md`.
2. Создай пустой файл `<vault-root>/INDEX.md` с минимальным frontmatter:
   ```yaml
   ---
   date: <today YYYY-MM-DD>
   tags: [index, navigation]
   ---

   # Index

   Каталог полей, evergreens, источников и троп. Обновляется на каждой операции.

   ## Fields

   ## Sources (raw)

   ## Evergreens

   ## Trails
   ```
3. Создай пустой файл `<vault-root>/log.md` с минимальным frontmatter:
   ```yaml
   ---
   date: <today YYYY-MM-DD>
   tags: [log]
   ---

   # Log

   Хронологический append-only журнал. Конвенция заголовка и тела — в `CLAUDE.md` (раздел «Логирование»).
   ```
4. Создай пустую папку `<vault-root>/trails/`.
5. Создай пустую папку `<vault-root>/_archive/`.
6. Проверь, что все пять артефактов на месте.
7. Установи `status: 4-done`.

## Ограничения

- Если файл/папка уже существует — оставляй как есть, не перезаписывай.
- `INDEX.md` и `log.md` создаются пустыми (заголовки разделов в INDEX, шапка в log); содержательные записи появятся на следующих шагах и при использовании скиллов.
