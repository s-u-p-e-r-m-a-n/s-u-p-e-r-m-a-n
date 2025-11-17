# 👋 Привет, я Sergey

Backend-разработчик на Java. Пишу сервисы на **Spring Boot** с упором на продакшн-подход: модульная архитектура, миграции БД, тесты, Docker, CI, документированное REST API.

---

## 🔧 Технологии

- **Ядро:** Java 17, Spring Boot 3, Spring MVC  
- **Безопасность:** Spring Security 6, JWT (access/refresh), роли, email-подтверждение  
- **REST и документация:** REST API (JSON, валидные HTTP-коды, валидация, единый формат ошибок), Swagger / OpenAPI (springdoc-openapi)  
- **Данные:** Spring Data JPA, PostgreSQL, H2, миграции с Flyway  
- **Маппинг:** MapStruct (DTO ↔ сущности, разделение слоёв)  
- **Тесты:** JUnit 5, Mockito, интеграционные тесты REST-контроллеров, Testcontainers (PostgreSQL + JUnit)  
- **Инфраструктура:** Maven, Docker, docker-compose, GitHub Actions (CI: сборка + тесты), Spring Boot Actuator  
- **Cloud / архитектура:** Spring Cloud Gateway, Netflix Eureka (Eureka Server + Eureka Client)

---

## 🏗 Портфолио-проект: Rent Apartment

[`rent-apartment-app`](https://github.com/s-u-p-e-r-m-a-n/rent-apartment-app) — многомодульный сервис аренды жилья:

- `architect-module` — схема БД и миграции Flyway  
- `auth-module` — аутентификация и авторизация пользователей  
  (JWT, роли, refresh-токены, email-подтверждение регистрации, Swagger UI)  
- `rent_module` — работа с объектами аренды и бронью (CRUD, просмотр, поиск, бронирование)  
- `product_module` — отдельный модуль для доменной логики товаров/объявлений  
- `email-sender` — сервис отправки кодов подтверждения на email  
- `api-getwey` — API Gateway (Spring Cloud Gateway + Eureka Client)  
- `eureka-server` — сервис-дискавери для микросервисов

На этом проекте я демонстрирую:

- реализацию **ролей и безопасного доступа** к API (Spring Security 6 + JWT + refresh)  
- проектирование и описание **REST API** с валидацией, единым форматом ошибок и документацией в Swagger / OpenAPI  
- разделение на модули и подготовку к **микросервисной архитектуре** (Eureka Server, API Gateway, отдельные сервисы)  
- работу с **реляционной БД** через JPA и миграции с Flyway  
- использование **MapStruct** для разделения доменной модели и DTO  
- написание **юнит- и интеграционных тестов** (в том числе с Testcontainers для PostgreSQL)  
- **контейнеризацию** (Docker, docker-compose) и **CI в GitHub Actions** для сборки и прогона тестов

Проект в активной разработке: по мере свободного времени добавляю новые сценарии и улучшаю архитектуру.
---

## 🔍 Что я ищу

Открыт к ролям:

- **Junior Java Backend Developer**  
- **Оплачиваемая стажировка (remote / part-time)**

---

## 📫 Контакты

Почта для рабочих предложений: **sergey.javadev@mail.ru**
