# home-mediaplayer

Данный проект разворачивает Apache Tomcat веб-сервер с интерфейсом на localhost:8080.

Он предоставляет возможность пользователю:
- Добавлять YouTube каналы которые ему интересны
- Просматривать список тегов
- Получать предложенные видео из добавленных каналов по тегу

Проект разрабатывался на Java 14 со сборщиком Gradle.

Для сборки: "gradlew bootRun" в корне проекта

Для использования перед запуском необходимо создать схему, SQL-скрипт для создания лежит в папке resources/SQL
