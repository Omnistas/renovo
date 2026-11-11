# Renovo BioEdil — главная страница

Статический сайт для GitHub Pages. Сборка не нужна.

## Что внутри
- `index.html` — главная страница
- `support.js`, `vendor/` — библиотеки, чтобы сайт не зависел от внешних серверов (кроме шрифтов Google Fonts)
- `assets/` — картинки и видео
- `.nojekyll` — отключает обработку Jekyll, оставьте файл

## Как опубликовать
1. Создайте аккаунт на github.com и новый репозиторий (New repository), например `renovo-site`. Тип: Public.
2. Загрузите в корень репозитория ВСЁ содержимое этой папки, включая скрытый файл `.nojekyll`:
   Add file → Upload files, перетащите файлы и папки, нажмите Commit changes.
3. Откройте Settings → Pages. В разделе Build and deployment выберите Source: Deploy from a branch, Branch: main, Folder: / (root), нажмите Save.
4. Подождите 1–2 минуты. Адрес сайта: `https://ВАШ-ЛОГИН.github.io/renovo-site/`

## Свой домен (по желанию)
Settings → Pages → Custom domain, введите домен и включите Enforce HTTPS. Затем у регистратора домена добавьте запись CNAME на `ВАШ-ЛОГИН.github.io`.

## Как обновлять
Заменяйте файлы в репозитории через Add file → Upload files (или `git push`). Сайт обновится через минуту.
