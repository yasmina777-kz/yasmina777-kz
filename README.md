<h2 align="center">Backend Developer</h2>

<p align="center">
  Python · FastAPI · Databases · AI integrations<br /><br />
  <a href="https://yasmina777-kz.github.io/portfolio/">portfolio ↗</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/yasmina777-kz?tab=repositories">repositories</a>
</p>

Я backend-разработчик. Создаю API, проектирую работу с базами данных и подключаю AI-сервисы к веб-приложениям. Основной фокус — **Python и FastAPI**. Также работаю с **ASP.NET Core** и пишу интерфейсы на React и Vue.

Мне интересны образовательные продукты: от серверной логики и доступа к данным до интерактивных лекций, чатов и проверки заданий.

### stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-171717?style=for-the-badge&amp;logo=python&amp;logoColor=D4D4D4" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-171717?style=for-the-badge&amp;logo=fastapi&amp;logoColor=D4D4D4" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-171717?style=for-the-badge&amp;logo=postgresql&amp;logoColor=D4D4D4" />
  <img alt=".NET" src="https://img.shields.io/badge/.NET-171717?style=for-the-badge&amp;logo=dotnet&amp;logoColor=D4D4D4" />
</p>

| Направление | Технологии |
| :--- | :--- |
| Backend | Python · FastAPI · C# · ASP.NET Core |
| Данные | PostgreSQL · SQLite · SQLAlchemy · EF Core |
| API и интеграции | REST · WebSockets · JWT · RAG · AI и speech API |
| Frontend | TypeScript · React · Vue 3 · Nuxt 3 · Pinia |

### selected projects

#### 01 / Chatra — образовательная платформа

Приложение для работы с классами, учебными материалами и заданиями. Сервер объединяет учебный процесс, общение и AI-инструменты; веб-интерфейс даёт доступ к ним из одного приложения.

**Что реализовано на backend:**

- **Авторизация:** регистрация, вход, access/refresh JWT-токены и роли пользователей.
- **Учебный процесс:** классы, задания, варианты работ, отправка решений, оценки и AI-проверка.
- **Общение:** чаты, сообщения и обновления в реальном времени через WebSockets.
- **Работа с материалами:** загрузка документов, извлечение текста, разбиение на фрагменты и поиск по ним с помощью RAG.
- **Лекции с аватаром:** генерация учебного контента, интеграции с озвучкой и видео, согласование публикации администратором.

Backend разделён на маршруты, схемы данных, CRUD-операции и сервисы. Во frontend — страницы классов, чатов и администрирования, общее состояние на Pinia и API-клиент с обновлением токенов.

`Python` `FastAPI` `SQLAlchemy` `WebSockets` `Vue 3` `Nuxt 3`

**[Backend →](https://github.com/yasmina777-kz/chatra-with-avatar-B)** · **[Frontend →](https://github.com/yasmina777-kz/chatra-with-avatar-F)**

---

#### 02 / AI Mentor — интерактивные лекции

Учебное приложение, в котором можно изучать тему, задавать вопросы голосом или текстом и закреплять материал практикой. Интерфейс и лекции поддерживают **русский, английский и казахский**.

**Что внутри:**

- Создание лекций по теме или материалам из PDF, DOCX, PPTX, TXT и Markdown.
- Вопросы во время лекции, заметки, тесты и сохранение прогресса.
- Серверные сессии с HttpOnly cookie, роли студента, преподавателя и администратора, проверка доступа к лекциям.
- Учебные группы с кодами приглашения, назначение лекций и просмотр результатов.
- Хранение данных через EF Core, поддержка SQLite и PostgreSQL, миграции базы данных.
- Учёт AI-запросов и расхода токенов, интеграция с синтезом речи.

`React` `TypeScript` `C#` `ASP.NET Core 8` `EF Core`

**[Код и инструкция запуска →](https://github.com/yasmina777-kz/lecturer-app)**

---

#### 03 / Portfolio — проекты и опыт

Личный сайт с отдельными страницами о себе, проектах, опыте и контактах. Переключение **RU / KZ / EN**, статические страницы без этапа сборки, публикация через GitHub Pages.

`HTML` `CSS` `JavaScript`

**[Открыть сайт ↗](https://yasmina777-kz.github.io/portfolio/)** · **[Исходный код →](https://github.com/yasmina777-kz/portfolio)**
