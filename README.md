# Конструктори постів Universe

Статичний сайт: кожна кампанія — окремий HTML-файл у `public/`, зібраний скілом employee-post-constructor.

## Перший деплой
1. GitHub → New repository → Private → `post-constructors-site`.
2. ```bash
   git init && git add . && git commit -m "init"
   git branch -M main
   git remote add origin https://github.com/<логін>/post-constructors-site.git
   git push -u origin main
   ```
3. Railway → New Project → Deploy from GitHub repo → обери репо. Змінних не потрібно.
4. Settings → Networking → Generate Domain.

## Нова кампанія
1. Поклади `<slug>.html` у `public/`.
2. Додай посилання в `public/index.html`.
3. `git add . && git commit -m "add <slug>" && git push` — Railway передеплоїть сам.

Посилання для колег: `https://<домен>/<slug>.html`
