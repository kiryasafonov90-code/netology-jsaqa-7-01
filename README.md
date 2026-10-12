# Нетология — 7.1 Использование JS в браузере. Тестирование, дебагинг

[Условие задания](https://github.com/netology-code/jsaqa-homeworks/blob/main/7-01.md)

## Задание 1 — настройка отладчика

Ветка `main` содержит `index.html` с текстом **hello world** и `.vscode/launch.json` для запуска Google Chrome из VS Code.

## Задание 2 — точки останова

Ветка `task-2-breakpoints` добавляет в `index.html`:

```js
const x = "hello world";
debugger;
console.log(x);
```

Нажмите F5 в VS Code. В конфигурации `Launch index.html` Chrome запустит HTML-файл и остановится на операторе `debugger`.

Затем установите точку останова слева от строки `console.log(x);` и повторите запуск (при необходимости продолжите выполнение после `debugger`). Сделайте два реальных скриншота и прикрепите их к Issue своего GitHub-репозитория. Откройте Pull Request из `task-2-breakpoints` в `main`.

> Скриншоты фактической работы VS Code должны быть выполнены на вашем компьютере. Они не могут быть заменены сгенерированными изображениями.

## Как опубликовать

Создайте пустой публичный репозиторий `netology-jsaqa-7-01` без README и `.gitignore` на GitHub. После этого из папки этого проекта:

```bash
git remote add origin https://github.com/ВАШ-ЛОГИН/netology-jsaqa-7-01.git
git push -u origin main
git push -u origin task-2-breakpoints
```

На GitHub создайте Pull Request из `task-2-breakpoints` в `main` и Issue со скриншотами.
