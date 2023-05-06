# REST API для списка задач
Перед запуском убедитесь, что вы установили Node.js версии 16 или выше.

Для запуска сервера перейдите в папку с репозиторием и выполните команду node index. Для остановки нажмите сочетание клавиш CTRL+C.
После запуска сервера API будет доступен по пути `http://localhost:8080`.

## Методы API
Все методы API, требующие тела запроса, ожидают получить тело в виде JSON. Ответы всех методов также отдаются в виде JSON.

* **GET /api/todo** получить список задач

* **POST /api/todo** создать список задач

* **GET /api/todo/{id}** получить данные списка задач по его ID

* **PUT /api/todo/{id}** перезаписать список задач с переданным ID.

* **DELETE /api/todo/{id}** удалить задачу с переданному ID.
