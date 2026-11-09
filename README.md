# Краснодар в движении

Интерактивная карта транспортных поездок в Краснодарском крае за 2025 год. Маршрут проходит через 30 населённых пунктов с данными. Линия на карте показывает порядок просмотра.

Для локального просмотра откройте `index.html` в браузере. Карта и данные встроены в этот файл.

## Публикация на GitHub Pages

Распакуйте весь архив и откройте PowerShell в папке `kuban-v-dvizhenii`. В архиве уже есть локальный репозиторий `.git`, ветка `main` и настроенный `origin`, который указывает на `jjoongrari/kuban-v-dvizhenii`.

```powershell
git status
git push
```

При запросе авторизации войдите в свой аккаунт GitHub.

В настройках репозитория откройте **Settings → Pages**. Источник публикации — **Deploy from a branch**, ветка **main**, папка **/ (root)**. Если этот источник уже сохранён, следите за запуском **pages build and deployment** во вкладке **Actions**.

- [GitHub Pages](https://github.com/jjoongrari/kuban-v-dvizhenii/settings/pages)
- [Статус публикации](https://github.com/jjoongrari/kuban-v-dvizhenii/actions)
- [Карта после публикации](https://jjoongrari.github.io/kuban-v-dvizhenii/)

## Дальнейшие обновления

После изменений карты или текста выполните из этой же папки:

```powershell
git add index.html README.md
git commit -m "Update Krasnodar transport map"
git push
```
