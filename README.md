# Алексей Хорьяков

### AI Automation Engineer · AI Integration · n8n · OpenAI · FastAPI · PostgreSQL

Создаю **AI-системы и автоматизацию для реальных бизнес-процессов** — от идеи и архитектуры до работающего backend, интеграций и production-развёртывания.

Мой фокус — не «прикрутить ChatGPT», а построить систему, в которой **AI, бизнес-логика, данные и автоматизация работают как единое целое**.

[![GitHub](https://img.shields.io/badge/GitHub-AlekseyHorjakov-181717?logo=github)](https://github.com/AlekseyHorjakov)
[![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71?logo=n8n)](https://n8n.io/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?logo=openai)](https://openai.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Data-4169E1?logo=postgresql)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-Infrastructure-2496ED?logo=docker)](https://www.docker.com/)

---

## 🚀 Основной проект — Orto-N-L-M / Ортона-AI

**AI-платформа для сбора экспертизы сотрудников, формирования корпоративной базы знаний и обучения персонала.**

Система превращает практический опыт сотрудника в структурированный **Process JSON**, а затем использует эти знания для формирования инструкций, обучения, тестирования и AI-помощи.

### Как работает концепция

```text
Эксперт
   ↓
AI-интервью
   ↓
Process JSON
   ↓
Корпоративные знания
   ├── Инструкции
   ├── Обучение
   ├── Тестирование
   └── AI-помощник
```

### Три пользовательские роли

| Роль | Возможности |
|---|---|
| 👔 Руководитель | Должности, инструкции, управление содержимым |
| 🧑‍💻 Специалист | AI-интервью, передача экспертизы, формирование процессов |
| 🎓 Стажёр | Изучение инструкций, тестирование, контроль знаний |

### Архитектура

```text
┌──────────────────────────────┐
│        Ортона-AI Web         │
│      React + Vite + CSS      │
└──────────────┬───────────────┘
               │ REST API
┌──────────────▼───────────────┐
│       FastAPI Backend        │
│   Auth · RBAC · Business API │
└──────────────┬───────────────┘
               │
┌──────────────▼───────────────┐
│          PostgreSQL          │
│ Users · Positions · Processes│
│ Sessions · Knowledge         │
└──────────────┬───────────────┘
               │
        ┌──────▼──────┐
        │     n8n     │
        │ AI / Logic  │
        └──────┬──────┘
               │
        ┌──────▼──────┐
        │   OpenAI    │
        └─────────────┘
```

### Что реализовано

- AI-интервью с адаптивной логикой;
- структурирование экспертных ответов в Process JSON;
- генерация инструкций на основе структурированных знаний;
- управление должностями и инструкциями;
- роли и разграничение доступа;
- серверная аутентификация;
- JWT;
- FastAPI REST API;
- PostgreSQL;
- React веб-интерфейс;
- обучение стажёров;
- тестирование знаний с механической проверкой;
- обработка файлов и материалов процесса;
- AI-раздел «Задать вопрос»;
- Docker-развёртывание;
- production deployment на Linux/VPS.

**Главный инженерный принцип:** Process JSON является каноническим источником знаний. Производные представления — инструкции, тесты и ответы AI — строятся на его основе.

👉 **[Репозиторий Orto-N-L-M](https://github.com/AlekseyHorjakov/Orto-N-L-M)**

---

## 🤖 JARVIS

Модульный персональный AI-ассистент с долговременной памятью и инструментами.

Проект использует:

- OpenAI API;
- AI Agent;
- Tool Calling;
- PostgreSQL;
- pgvector;
- семантический поиск;
- Docker;
- SSH и Docker-инструменты;
- SearXNG;
- долгосрочную память.

👉 **[Репозиторий JARVIS](https://github.com/AlekseyHorjakov/JARVIS)**

---

## 🧠 Что умею

### AI & Automation

- AI Agents
- Prompt Engineering
- OpenAI API
- AI Workflow Design
- n8n
- бизнес-автоматизация
- AI-интервью и knowledge extraction
- AI-консультанты и чат-боты

### Backend & Integration

- FastAPI
- REST API
- Webhooks
- JSON
- JWT / RBAC
- SQL
- PostgreSQL
- pgvector

### Infrastructure

- Linux / Ubuntu Server
- Docker / Docker Compose
- VPS
- reverse proxy
- HTTPS / SSL
- серверное развёртывание
- диагностика и сопровождение инфраструктуры

### Development

- Python
- JavaScript
- React
- Vite
- Git / GitHub

---

## 🛠 Инженерный подход

Я предпочитаю строить решения по принципу:

**бизнес-задача → архитектура → данные → автоматизация → AI → production**

AI не должен заменять бизнес-логику там, где решение можно сделать детерминированным. Поэтому в проектах разделяю:

- **детерминированную логику** — маршрутизация, права, CRUD, проверки;
- **AI-логику** — интервью, структурирование знаний, генерация и работа с естественным языком;
- **данные** — PostgreSQL и структурированные модели;
- **оркестрацию** — n8n;
- **пользовательский слой** — собственный веб-интерфейс и API.

Такой подход делает систему предсказуемее, проще для отладки и пригоднее для реального бизнеса.

---

## 💼 Профессиональный профиль

Много лет работаю в IT и системном администрировании: Linux и Windows, серверы, сети, VPS, Docker, сопровождение сервисов и решение инфраструктурных проблем.

Сейчас специализируюсь на **AI automation и AI integration** — соединяю существующую IT-инфраструктуру, API, базы данных, n8n и LLM в законченные рабочие системы.

Мне интересны задачи, где требуется не просто написать код, а **понять процесс, спроектировать решение и довести его до работающего результата**.

---

## 📌 Сейчас развиваю

- Orto-N-L-M / Ортона-AI;
- AI automation;
- AI agents;
- корпоративные knowledge systems;
- AI-интеграции;
- production-ready n8n workflows;
- RAG и семантический поиск.

---

## 📫 Контакты

- **GitHub:** [AlekseyHorjakov](https://github.com/AlekseyHorjakov)
- **Email:** a.horjakoff@gmail.com
- **Telegram:** [@a_horjakoff](https://t.me/a_horjakoff)

---

> **AI имеет смысл тогда, когда превращается в работающий бизнес-инструмент.**
