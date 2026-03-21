# Привет, я Sergey

Java backend developer. Разрабатываю backend-сервисы и backend-модули на Spring Boot с упором на authentication, roles, REST API, PostgreSQL и Docker.

* * *

## 🚀 Главная витрина

### [spring-auth-service](https://github.com/s-u-p-e-r-m-a-n/spring-auth-service)
Standalone backend-сервис аутентификации и авторизации на Spring Boot.

Что реализовано:
- регистрация пользователей
- подтверждение регистрации через код
- авторизация по логину и паролю
- JWT access / refresh tokens
- ролевая модель (`GUEST`, `USER`, `ADMIN`, `SUPER_ADMIN`)
- Swagger UI
- Flyway migrations
- Docker / Docker Compose
- unit + integration tests

### [rent-apartment-app](https://github.com/s-u-p-e-r-m-a-n/rent-apartment-app)
Основной backend-monorepo сервиса аренды жилья.  
`spring-auth-service` вырос из этого проекта как отдельный showcase-ready сервис, а остальная платформа находится в активной разработке.

* * *

## 🛠 Технологии

- **Java / Spring:** Java 17, Spring Boot 3, Spring MVC
- **Security:** Spring Security 6, JWT (access / refresh), роли, email-подтверждение
- **REST / API:** REST API, валидация, единый формат ошибок, Swagger / OpenAPI
- **Data:** Spring Data JPA, PostgreSQL, H2, Flyway
- **Mapping:** MapStruct
- **Testing:** JUnit 5, Mockito, Testcontainers
- **Infrastructure:** Maven, Docker, Docker Compose, GitHub Actions
- **Cloud / Architecture:** Spring Cloud Gateway, Eureka

* * *

## 🧩 Что умею делать

- backend-сервисы на Java / Spring Boot
- authentication / authorization
- JWT, роли, защищённые endpoint'ы
- REST API и CRUD-логику
- PostgreSQL + Flyway migrations
- Docker / Docker Compose
- доработку существующего backend-кода
- unit и integration tests

* * *

## 🏠 Rent Apartment App — активная разработка

В основном monorepo развиваю платформу аренды жилья с многомодульной архитектурой.

Ключевые части проекта:
- `auth-module` — аутентификация и авторизация
- `rent_module` — бизнес-логика аренды, объекты, комментарии, рейтинги, фото, интеграции
- `email-sender` — отправка кодов подтверждения
- `api-gateway` — единая точка входа
- `eureka-server` — service discovery
- `architect-module` — схема БД и миграции

Проект использую как основную техническую базу для развития backend-архитектуры, доменной логики и новых сервисных сценариев.

* * *

## 📫 Контакты

Почта для рабочих предложений: sergey.javadev@mail.ru
