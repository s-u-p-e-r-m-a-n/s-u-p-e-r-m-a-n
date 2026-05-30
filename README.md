# Привет, меня зовут Сергей!

Я Java backend-разработчик. Разрабатываю backend-сервисы и backend-модули на Spring Boot: REST API, бизнес-логика, PostgreSQL, Docker, интеграции с внешними API и тестирование.

На GitHub отдельно показываю сервис авторизации на Spring Boot, Telegram-бота для приёма заявок бизнеса и основной многомодульный backend-проект rent-apartment-app с микросервисной архитектурой, бизнес-логикой, REST API, Gateway, Eureka, миграциями и интеграциями.

* * *

## 🚀 Главная витрина

### [spring-auth-service](https://github.com/s-u-p-e-r-m-a-n/spring-auth-service)
Отдельный backend-сервис аутентификации и авторизации на Spring Boot.

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

### [telegram-lead-bot](https://github.com/s-u-p-e-r-m-a-n/telegram-lead-bot)

Telegram-бот для приёма заявок от клиентов.

Что реализовано:

* сценарий сбора заявки через Telegram
* сохранение заявок в PostgreSQL
* уведомление администратора о новой заявке
* admin-команды для просмотра последних заявок
* базовая статистика
* Flyway migrations
* Docker / Docker Compose
* unit tests

### [rent-apartment-app](https://github.com/s-u-p-e-r-m-a-n/rent-apartment-app)
Основной многомодульный backend-проект сервиса аренды жилья с микросервисной архитектурой.
Что показывает проект:

- отдельные сервисы и инфраструктурные модули
- единый вход через API Gateway
- service discovery через Eureka
- REST API и доменную бизнес-логику
- работу с PostgreSQL и миграциями
- интеграции и сервисное взаимодействие
- развитие backend-платформы через отдельные модули
  
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
- ** Telegram: Telegram Bot API, long polling, admin-команды, уведомления
  
* * *

## 🧩 Что умею делать

- Разрабатывать backend-сервисы на Java / Spring Boot
- Проектировать REST API и серверную бизнес-логику
- Настраивать авторизацию и роли: Spring Security, JWT, refresh tokens
- Работать с PostgreSQL, JPA/Hibernate, Flyway migrations
- Разрабатывать Telegram-ботов для бизнес-задач: заявки, уведомления, admin-команды, хранение данных в БД
- Интегрировать backend с внешними API и сервисами
- Документировать API через Swagger / OpenAPI
- Упаковывать приложения в Docker / Docker Compose
- Писать unit- и integration-тесты
- Настраивать GitHub Actions CI для сборки и проверки проекта


* * *

## 🏠 Rent Apartment App — активная разработка

В основном monorepo развиваю платформу аренды жилья с многомодульной backend-архитектурой и отдельными сервисами.

Ключевые части проекта:
- `auth-module` — аутентификация и авторизация
- `rent_module` — бизнес-логика аренды, объекты, комментарии, рейтинги, фото, интеграции
- `email-sender` — отправка кодов подтверждения
- `api-gateway` — единая точка входа
- `eureka-server` — service discovery
- `architect-module` — схема БД и миграции

Проект использую как основную техническую базу для развития backend-архитектуры, доменной логики, интеграций и новых сервисных сценариев.

* * *

## 📫 Контакты

Почта для рабочих предложений: sergey.javadev@mail.ru
