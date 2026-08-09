# P4K Deck — AI Workflow

Презентация «Один человек + AI-команда» (Pe4King) как standalone web-приложение.

**Live:** https://mdyuzhev.github.io/p4k-deck/

## Структура

- `index.html` — сама презентация (слайды, стили, speaker notes)
- `deck-stage.js` — web component `<deck-stage>`: навигация, масштабирование, thumbnail rail, print-to-PDF

## Управление

- `←` / `→`, `Space`, `PgUp` / `PgDn` — навигация по слайдам
- `Home` / `End` — первый / последний слайд
- цифры — прыжок на слайд
- `R` — сброс на первый слайд
- Print → Save as PDF — экспорт по слайду на страницу

## Локальный запуск

Открыть `index.html` в браузере — сборка не требуется.
