# Student

Учёт студентов. Бэкенд на основе [проекта преподавателя](https://github.com/dorzhogun/fun-student), фронт на HTML, CSS и JavaScript.

## Запуск

Java 21 и PostgreSQL. Создать базу `students_db` (пользователь и пароль `postgres`).

```sh
sh mvnw spring-boot:run
```

На Windows: `mvnw.cmd spring-boot:run`. Адрес: http://localhost:8080.

## Вход

| Роль | Логин | Пароль |
| --- | --- | --- |
| Администратор | admin@example.com | admin |
| Преподаватель | teacher@example.com | teacher |
| Суперадминистратор | superadmin@example.com | superAdmin |
