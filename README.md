
# Flask Review Lab: вариант A+B


Учебное Flask-приложение для лабораторной работы 2: ветвление Git, Pull Request и проверка изменений.

## Требования

- Python 3.12
- Git

## Установка

```bash
python -m venv .venv
source .venv/bin/activate          # Linux/macOS
source .venv/Scripts/activate      # Windows, Git Bash
python -m pip install -r requirements.txt
```

## Запуск сервера

```bash
python app.py
```

Откройте http://127.0.0.1:8080, должно отображаться `Hello, World!`. Остановка: Ctrl+C.

## Запуск тестов

```bash
python -m pytest -q
```

## Доступные URL

- `/` — приветствие `Hello, World!`
- `/about` — текстовое описание проекта
- `/health` — проверка состояния, возвращает JSON `{"status":"ok"}`

