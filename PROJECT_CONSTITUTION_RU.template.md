# 📜 PROJECT CONSTITUTION

## Каноническая конституция проекта (AI Engineering Standard — AES)

AES Constitution Version: 1.0  
Status: Active  
Authority Level: Required

---

## ⚖️ АВТОРИТЕТ КОНСТИТУЦИИ

Этот документ определяет **продуктовую и архитектурную истину проекта**.

Все AI-агенты и разработчики, работающие в репозитории, ОБЯЗАНЫ:

- следовать решениям, описанным в данной конституции
- не отклоняться от архитектуры без подтверждения человека
- запрашивать уточнение при конфликте решений
- считать данный документ приоритетнее предположений

Если реализация противоречит конституции —  
**конституция имеет приоритет.**

Этот файл является **единым источником истины системы**.

---

## 🤖 КОНТЕКСТ ИСПОЛНЕНИЯ AI

AI-агент обязан:

1. Прочитать конституцию перед генерацией кода
2. Построить план реализации
3. Работать итеративно
4. Проверять изменения на соответствие конституции

🚫 Реализация НЕ начинается без согласования плана.

---

# 1. 🎯 PRODUCT SCOPE

## Описание проекта

Название:
Одно предложение:
Целевой пользователь:

---

## MVP Scope (≤5 пунктов)

---

## Non-Goals (НЕ входит в MVP)

❌
❌
❌

---

## Метрики успеха

| Метрика          | Цель         | Измерение  |
| ---------------- | ------------ | ---------- |
| Главная функция  | Да           | Smoke test |
| Время ответа     | < \_\_\_ сек | P95        |
| Покрытие тестами | > \_\_\_%    | CI         |

---

# 2. 🛠️ ТЕХНОЛОГИЧЕСКИЙ СТЕК

## Frontend

Framework:
Language:
Styling:
State Management:
Routing:
HTTP Client:
UI Library:
Validation:

## Backend

Framework:
Database:
ORM:
Auth:
File Storage:

## Infrastructure

Package Manager:
Runtime:
Deployment:
Hosting:

---

# 3. 📐 АРХИТЕКТУРА

## Архитектурный подход

Pattern:
Layer separation:
API isolation:
Error handling:

---

## Структура проекта

src/
├── api/
├── components/
├── pages/
├── hooks/
├── utils/
└── types/

---

# 4. 👤 USER FLOWS

FLOW 1:
Пользователь → → Результат

FLOW 2:
Пользователь → → Результат

---

# 5. 📋 FUNCTIONAL REQUIREMENTS

## User Stories

P0:

Как пользователь, я хочу \_\_\_

P1:

P2:

---

# 6. ⚡ НЕФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ

## Performance

API latency P95:
Page load:
Bundle size:

## Reliability

Uptime target:
Healthcheck:
/health → 200 OK

## Security

Authentication:
Rate limiting:
Input validation:
HTTPS:

---

# 7. 🗄️ DOMAIN MODEL

Entity1 1:M Entity2

---

# 8. 🚀 DEPLOYMENT

Platform:
Environment variables:
CI/CD:
Rollback strategy:

---

# 9. ✅ ACCEPTANCE CRITERIA

Feature считается завершённой если:

[ ] Работает happy path
[ ] Обработаны ошибки
[ ] Типизация без ошибок
[ ] Responsive UI
[ ] Loading / Empty / Error states

---

# 🔁 ЭВОЛЮЦИЯ КОНСТИТУЦИИ

Конституция может изменяться только при:

- явном подтверждении человека
- архитектурном ревью
- обновлении версии документа

---

_AI Engineering Standard (AES)_
