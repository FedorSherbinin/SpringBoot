# Spring Boot Web Application

## Описание
Это простое веб-приложение на Spring Boot, которое приветствует пользователя на главной странице.

## Стек технологий
- Spring Boot 3.2.1
- Java 17
- Gradle

## Установка

### Предварительные требования
- Java JDK 17 или выше
- Gradle 7.0 или выше

### Клонирование репозитория
Сначала клонируйте репозиторий:

```bash
git clone <URL вашего репозитория>
cd <имя_директории>
Сборка проекта
Убедитесь, что все зависимости установлены:

./gradlew build
Запуск приложения
Запустите приложение с помощью Gradle:

./gradlew bootRun
После успешного запуска приложение будет доступно по адресу http://localhost:8080/.

Тестирование
Откройте браузер и перейдите по следующему URL:

http://localhost:8080/

Вы должны увидеть сообщение: Привет, пользователь!

Структура проекта
.
├── build.gradle
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── demo
│   │   │               ├── SpringBootWebApplication.java
│   │   │               └── GreetingController.java
│   │   └── resources
│   │       └── application.properties
└── README.md
