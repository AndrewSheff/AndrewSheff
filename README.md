> **[English version](README_EN.md)**

<!--
  BANNER: сгенерировать изображение 1280x320, темный градиент #0f172a → #1e293b,
  текст "ANDREW SHEFF" белым Inter Bold, подтекст "Full-Stack Developer | Python + React + AI"
  цветом #94a3b8, тонкая линия #3b82f6 внизу, без иконок
  Сохранить как assets/banner.png и раскомментировать строку ниже:
-->
<!-- <img src="assets/banner.png" alt="Andrew Sheff — Full-Stack Developer" width="100%"> -->

<div align="center">

# Андрей Шевцов

**Full-Stack разработчик — Java + Python + AI**

Создаю production-ready бизнес-платформы, которые реально работают.

[![Java](https://img.shields.io/badge/Java-21-ED8B00?logo=openjdk&logoColor=white)](https://openjdk.org)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.3-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Python](https://img.shields.io/badge/Python-3.13-3776AB?logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](https://docker.com)

**10 коммерческих платформ** · **76 000+ строк кода** · **329 API-эндпоинтов** · **285+ тестов**

</div>

---

### Java — Enterprise Backend

<table>
<tr>
<td width="50%" valign="top">

#### [OrderHub](https://github.com/AndrewSheff/orderhub)

Микросервисная OMS для e-commerce: CQRS, Event Sourcing (без Axon), мультискладская логика, курсорная пагинация.

`4 900 строк` · `31 эндпоинт` · `25 тестов`

Spring Boot 3 · Kafka · PostgreSQL · Spring Modulith

</td>
<td width="50%" valign="top">

#### [FinFlow](https://github.com/AndrewSheff/finflow)

Платежный процессинг: стейт-машина платежей, двойная запись, anti-fraud движок, Outbox + Kafka.

`4 800 строк` · `24 эндпоинта` · `22 теста`

Spring Boot 3 · Spring Statemachine · Kafka · Quartz

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [GateKeeper](https://github.com/AndrewSheff/gatekeeper)

API Gateway + OAuth2 сервер: аутентификация, API-ключи, rate limiting, динамическая маршрутизация, аналитика трафика.

`5 500 строк` · `33 эндпоинта` · `39 тестов`

Spring Boot 3 · Spring Security · Redis · Caffeine

</td>
<td width="50%" valign="top">

#### [DocVault](https://github.com/AndrewSheff/docvault)

СЭД: маршруты согласования, версионирование, полнотекстовый поиск, оргструктура, RBAC.

`4 000 строк` · `32 эндпоинта` · `9 тестов`

Spring Boot 3 · MinIO · Apache Tika · PostgreSQL tsvector

</td>
</tr>
</table>

<div align="center">

#### [NotifyX](https://github.com/AndrewSheff/notifyx)

Мультиканальные уведомления: email/SMS/push/Telegram, шаблоны, приоритетные очереди, Circuit Breaker, DLQ.

`3 900 строк` · `17 эндпоинтов` · `10 тестов`

Spring Boot 3 · Kafka · Resilience4j · Virtual Threads

</div>

---

### Python — AI и автоматизация

<table>
<tr>
<td width="50%" valign="top">

#### [Telegram Business Assistant](https://github.com/AndrewSheff/telegram-business-assistant)

Telegram-бот платформа для бизнеса: онлайн-запись, AI-чат, переключение на оператора, рассылки, CRM с аналитикой.

`16 800+ строк` · `55 эндпоинтов` · `48 тестов`

FastAPI · React · aiogram 3 · PostgreSQL · Redis

</td>
<td width="50%" valign="top">

#### [CRM Lite](https://github.com/AndrewSheff/crm-lite)

Легковесная CRM: клиенты, канбан-доска сделок (drag & drop), воронка продаж, AI-ассистент, Excel-экспорт. Без ежемесячных платежей.

`10 000+ строк` · `47 эндпоинтов` · `9 моделей`

FastAPI · React · @dnd-kit · PostgreSQL · Redis

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Smart Scraper Platform](https://github.com/AndrewSheff/smart-scraper-platform)

SaaS для мониторинга сайтов: расписание, CSS/XPath-селекторы, обнаружение изменений, AI-саммари, Telegram-алерты.

`10 400+ строк` · `31 эндпоинт` · `48+ тестов`

FastAPI · React · BeautifulSoup · APScheduler

</td>
<td width="50%" valign="top">

#### [AI Support Agent](https://github.com/AndrewSheff/ai-support-agent)

Корпоративный AI-ассистент: RAG-пайплайн, семантический поиск по документам, ответы со ссылками на источники.

`9 500+ строк` · `22 эндпоинта` · `42 теста`

FastAPI · React · OpenAI · pgvector

</td>
</tr>
</table>

<div align="center">

#### [AI Document Processor](https://github.com/AndrewSheff/ai-document-processor)

Анализ документов: загрузка PDF/DOCX/XLSX, семантический поиск (pgvector), Q&A с цитатами, AI-аналитика.

`6 200+ строк` · `37 эндпоинтов` · `7 моделей` · `pgvector HNSW`

FastAPI · React · OpenAI embeddings · PostgreSQL

</div>

---

### В каждом проекте

| | | | |
|:---:|:---:|:---:|:---:|
| **Docker Compose** | **CI/CD** | **Тесты** | **Swagger UI** |
| Запуск одной командой | GitHub Actions | JUnit 5 / Pytest | Полная документация API |
| **Авторизация** | **Миграции** | **Логирование** | **MIT лицензия** |
| Spring Security / JWT | Liquibase / Alembic | Logback / structlog | Бесплатно для коммерции |

---

### Стек

| Java Enterprise | Python & AI | Фронтенд | Инфраструктура |
|:---------------|:------------|:---------|:---------------|
| Java 21 (LTS) | Python 3.13 | React 19 | Docker Compose |
| Spring Boot 3.3 | FastAPI 0.115 | TypeScript 5+ | GitHub Actions CI/CD |
| Spring Security 6 | SQLAlchemy 2.0 | Vite 6 | Kafka |
| Spring Data JPA | OpenAI GPT-4 | TailwindCSS v4 | Redis 7 |
| Kafka + Resilience4j | pgvector + RAG | shadcn/ui | PostgreSQL 16 |
| Liquibase · MapStruct | Alembic · Pytest | React Query | Prometheus + Micrometer |

---

### Сотрудничество

Открыт для фриланса и контрактной работы. Java — enterprise и высокие нагрузки. Python — AI и автоматизация. Готовые продукты под ключ.

[![Email](https://img.shields.io/badge/Email-andrew.sheff2012@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:andrew.sheff2012@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@Andrey__Shevtsov1-26A5E4?logo=telegram&logoColor=white)](https://t.me/Andrey_Shevtsov1)
