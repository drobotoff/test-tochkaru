# Test for TochkaRu

Тестовое задание:

1. Развернуть Laravel (commit init)
2. Установить на него voyager (commit voyager)
3. Сделать кастомный контроллер для новости (posts), наследованный от контроллера админ-панели по умолчанию + кастомный шаблон редактирования

*Особенность доработки в следующем: при сохранении типа ввода поля title  (Text), изменить формат отображения именно этого поля на странице редактирования в качестве Textarea. (commit edit title)*

Логика работы механизма BREAD не должна пострадать, любые изменения/добавления полей в админ-панели должны применяться к пользовательскому интерфейсу, как это работает по умолчанию

---

В проекте импользуется Voyager (https://voyager-docs.devdojo.com/)

---

##Запуск проекта

1. Изменить .env

```
    APP_URL=http://localhost
    DB_HOST=localhost
    DB_DATABASE=homestead
    DB_USERNAME=homestead
    DB_PASSWORD=secret    
```

2.

```
php artisan migrate
php artisan serve
```

3.

```
http://localhost:8000/admin
email: admin@admin.com
password: password
```
