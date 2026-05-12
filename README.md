# Wedding Invitation

Одностраничный статический сайт-приглашение.

## Локальный запуск

```bash
npm run start
```

Сайт будет доступен по адресу `http://localhost:4173`.

## Структура

- `index.html` — основная страница
- `assets/styles/main.css` — стили
- `assets/scripts/main.js` — скрипты
- `assets/images/` — изображения
- `assets/fonts/` — шрифты

## Деплой на GitHub Pages

В проект уже добавлен workflow для GitHub Pages: `.github/workflows/deploy-pages.yml`.

Что нужно сделать:

1. Создать репозиторий на GitHub.
2. Привязать локальный проект к репозиторию и запушить код в ветку `main` или `master`.
3. В GitHub открыть `Settings` → `Pages`.
4. В разделе `Build and deployment` выбрать `Source: GitHub Actions`.
5. После пуша дождаться завершения workflow `Deploy static site to GitHub Pages`.

После этого сайт будет доступен по адресу вида:

`https://USERNAME.github.io/REPOSITORY-NAME/`

## Примечание

Сайт полностью статический, поэтому отдельная сборка не нужна: GitHub Actions публикует готовые файлы напрямую.
