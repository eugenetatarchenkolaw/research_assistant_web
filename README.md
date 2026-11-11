# Research Assistant · OpenRouter Lab

Публичная браузерная версия Research Assistant для исследования документов ГОСТ с поиском BM25, анализом чанков, оценкой качества TOP-k, визуализациями и генерацией вопросов через OpenRouter.

## Запуск

- **GitHub Pages:** https://eugenetatarchenkolaw.github.io/research_assistant_web/ (после включения GitHub Pages).
- Основная страница: [index.html](index.html).
- Оригинал: [research_assistant_openrouter.html](research_assistant_openrouter.html). Файлы идентичны.

## Включение GitHub Pages

1. Откройте https://github.com/eugenetatarchenkolaw/research_assistant_web/settings/pages
2. В **Build and deployment** выберите **Source: Deploy from a branch**.
3. Выберите **Branch: main**, **Folder: /(root)**, затем **Save**.
4. Проверьте публикацию на странице Settings → Pages или Actions. Адрес станет доступен после успешного развёртывания.

## Ограничения и конфиденциальность

- HTML, CSS и основная логика JavaScript встроены в одну страницу. Для работы с PDF библиотека PDF.js загружается из CDN, поэтому нужен интернет.
- Для OpenRouter нужен личный API-ключ, вводимый только в интерфейсе браузера. **Не добавляйте API-ключ в репозиторий.** Доступность запросов зависит от OpenRouter, выбранной модели и CORS.
- Работа с загруженными пользователем документами происходит в браузере, однако при запуске генерации выбранные данные отправляются во внешний API согласно интерфейсу.
- Публичный HTML включает контактный email и встроенные исходники Python, видимые всем посетителям.
- Для сохранения состояния используйте кнопку «Сохранить проект»; GitHub Pages не предоставляет серверное хранение пользовательских проектов.

Изначальный репозиторий `research_assistant` не используется для этой публикации.
