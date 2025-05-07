# Деплой системи на Render

Цей проєкт підтримує автоматичне розгортання на [Render.com](https://render.com).

---

## Швидкий запуск:

1. Форкни або клонуй репозиторій
2. Додай файл `render.yaml` у корінь проєкту (вже включено)
3. Перейди на [Render.com](https://render.com)
4. Обери: **"New > Blueprint"**
5. Обери цей репозиторій
6. Render самостійно створить два сервіси:
   - `stock-backend` — FastAPI (порт 8000)
   - `stock-frontend` — React (порт 3000)

---

## Деталі

### Backend:
- Dockerfile: `Dockerfile.backend`
- Старт: `uvicorn main:app`
- Документація: `https://.../docs`

### Frontend:
- Dockerfile: `Dockerfile.frontend`
- Команда: `npm start`

---

## Що отримаєш:

- **Live система** в браузері
- Автоматичне оновлення при `git push`
- Демонстрація для команди або інвесторів

