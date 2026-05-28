---
type: task
status: 1-open
created: 2026-05-28
field: forest-framework
---

# 01 — Установка схем

Скопировать `_schemas/` из репозитория FOREST в корень vault пользователя.

## Шаги

1. Проверь, что `forest-framework/_schemas/` существует и содержит `skills/` и `templates/`.
2. Определи путь корня vault. Если неясно — спроси пользователя.
3. Скопируй целиком `forest-framework/_schemas/` в `<vault-root>/_schemas/`.
4. Сверь структуру: в `<vault-root>/_schemas/` должны быть `skills/` (с `process-observation.md`, `initialize-field.md`, `reflection.md`, `lint.md`) и `templates/` (с `template-evergreen.md`, `template-observation.md`, `template-reflection.md`, `template-field.md`, `template-trail.md`).
5. Установи у этой задачи `status: 4-done`.

## Ограничения

- Содержимое файлов при копировании не модифицируется.
- Если `<vault-root>/_schemas/` уже существует (сценарий обновления) — спроси пользователя перед перезаписью.
