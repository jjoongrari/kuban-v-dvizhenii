# Краснодар в движении

Интерактивная карта транспортных поездок в Краснодарском крае за 2025 год. Автобус проходит через 30 населённых пунктов с данными. Линия на карте показывает порядок просмотра.

Карта, данные и подложка встроены в `index.html`. Для локального просмотра откройте файл в браузере. Для GitHub Pages сборка не нужна.

## Первый запуск на GitHub Pages

1. Создайте пустой публичный репозиторий на GitHub без README, лицензии и `.gitignore`.
2. Распакуйте архив и откройте Git Bash в папке `kuban-v-dvizhenii`, где лежит `index.html`.
3. Замените `USERNAME` и `REPOSITORY` в URL на имя своего аккаунта и репозитория. Выполните команды.

```bash
git init -b main
git add index.html .nojekyll README.md
git commit -m "Add Krasnodar transport map"
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

4. Откройте настройки репозитория. В **Settings → Pages → Build and deployment** выберите **Deploy from a branch**, ветку **main** и папку **/ (root)**. Нажмите **Save**.
5. После публикации откройте ссылку на сайт в **Settings → Pages**.

## Обновление существующего сайта

В локальной копии репозитория замените `index.html` в папке, из которой публикуется сайт. Если в этой папке ещё нет `.nojekyll`, скопируйте его из архива. Для сайта с источником `/docs` папкой публикации будет `docs`.

Выполните команды из папки публикации, находясь на ветке, настроенной в Pages.

```bash
git add index.html .nojekyll
git commit -m "Update Krasnodar transport map"
git push
```

[Документация GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
