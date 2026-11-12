# Сергей — Java Backend Developer

Разрабатываю веб-приложения, backend-сервисы и интеграции на **Java, Spring Boot и Spring Security**. Проектирую REST API, реализую бизнес-логику, аутентификацию и права доступа, работу с PostgreSQL и взаимодействие с внешними системами.

Работаю над полным сценарием приложения — от модели данных и серверной логики до пользовательского интерфейса, тестирования и развёртывания. Для веб-интерфейсов использую React и TypeScript.

Интересуют разработка новых продуктов и развитие существующих систем, технически содержательные задачи и сотрудничество с командами. Среди направлений — backend, API-интеграции, автоматизация бизнес-процессов и приложения для работы с заказами и данными.

## Что делаю

- **Backend и API** — разработка сервисов на Spring Boot, REST API, бизнес-логика, валидация запросов, обработка ошибок и документация OpenAPI.
- **Аутентификация и доступ** — Spring Security, JWT access/refresh tokens, ротация токенов, роли и защита эндпоинтов.
- **Данные** — проектирование сущностей и связей, PostgreSQL, JPA/Hibernate, транзакции и миграции Flyway.
- **Интеграции** — подключение внешних API, обмен данными, платёжные сценарии, Telegram-боты и уведомления.
- **Обработка заказов** — расчёт стоимости, резервирование остатков, управление статусами и идемпотентность операций.
- **Веб-интерфейсы** — React, TypeScript, пользовательские страницы и административные панели.
- **Тестирование и поставка** — unit- и integration-тесты, Docker Compose, настройка CI в GitHub Actions.

## Технологии

| Направление | Стек |
|---|---|
| Java / Spring | Java 17, Spring Boot 3, Spring MVC, Spring Security 6, Spring Data JPA |
| API и безопасность | REST, HTTP, JWT, Bean Validation, Swagger / OpenAPI |
| Базы данных | PostgreSQL, Hibernate, Flyway, H2 |
| Тестирование | JUnit 5, Mockito, Testcontainers, JaCoCo |
| Frontend | React, TypeScript, Vite |
| Интеграции | Telegram Bot API, Telegram Mini Apps, ЮKassa API |
| Сборка и инфраструктура | Git, Maven, Docker, Docker Compose, Nginx, GitHub Actions |
| Микросервисы | Spring Cloud Gateway, Eureka, межсервисное взаимодействие |

## Избранные проекты

### [Telegram Mini App Shop](https://github.com/s-u-p-e-r-m-a-n/telegram-miniapp-shop)

Система продаж, объединяющая **Mini App, Telegram-бота, Java backend и веб-панель управления**.

Покупатель выбирает товары, оформляет заказ и получает уведомления. Администратор управляет каталогом, остатками и заказами, меняет статусы и связывается с клиентом.

Техническая часть:

- серверный расчёт суммы заказа и резервирование товаров;
- транзакции и блокировки при изменении остатков;
- идемпотентность создания заказа и оплаты;
- интеграция с Invoice API ЮKassa и фоновая сверка состояния счетов;
- проверка подписи Telegram initData и принадлежности заказа пользователю;
- административный доступ через Spring Security;
- React-интерфейсы витрины и панели управления;
- Flyway, Docker Compose, Nginx и GitHub Actions.

**Стек:** Java, Spring Boot, Spring Security, PostgreSQL, JPA/Hibernate, React, TypeScript, Telegram Bot API, ЮKassa API.

### [Spring Auth Service](https://github.com/s-u-p-e-r-m-a-n/spring-auth-service)

Сервис аутентификации и авторизации на **Spring Boot и Spring Security**.

- Регистрация и подтверждение через код.
- JWT access/refresh tokens и ротация refresh-токенов.
- Ролевая модель и административные API.
- Валидация DTO и централизованная обработка ошибок.
- PostgreSQL и миграции Flyway.
- Swagger / OpenAPI.
- Unit- и integration-тесты с JUnit, Mockito и Testcontainers.
- Профили запуска и Docker Compose.

### [Telegram Lead Bot](https://github.com/s-u-p-e-r-m-a-n/telegram-lead-bot)

Бот для приёма и обработки клиентских заявок.

Пошагово собирает данные клиента, сохраняет заявку в PostgreSQL и отправляет уведомление администратору. Предусмотрены просмотр последних заявок, базовая статистика, миграции базы и unit-тесты.

**Стек:** Java, Spring Boot, Spring Data JPA, PostgreSQL, Flyway, Docker Compose.

### [Rent Apartment App](https://github.com/s-u-p-e-r-m-a-n/rent-apartment-app)

Многомодульный проект, демонстрирующий микросервисную архитектуру backend-приложения.

Отдельные сервисы авторизации и бизнес-логики аренды, маршрутизация через **Spring Cloud Gateway**, обнаружение сервисов через **Eureka**, REST API, PostgreSQL и интеграция с внешним API геолокации.

Подробности реализации и текущий статус модулей — в README репозитория.

## Работа и сотрудничество

Открыт к проектной и частичной занятости, сотрудничеству с продуктовыми командами, студиями и интеграторами.

Рассматриваю разработку отдельных сервисов и модулей, API-интеграции, доработку Java-приложений и создание веб-приложений с backend и пользовательским интерфейсом.

Объём, сроки, загрузку и порядок взаимодействия согласуем под задачи проекта.

## Контакты

**Сергей · Липецк · удалённое сотрудничество**

[sergey.javadev@mail.ru](mailto:sergey.javadev@mail.ru)
