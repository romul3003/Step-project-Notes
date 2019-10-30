# Step-project-Notes

#### Application on heroku:

https://step-project-notes.herokuapp.com/

#### Спискок использованных технологий:
- JavaScript
- Node.js
- Express
- Mongoose
- Pug
- Bootstrap

#### Состав участников проекта

- Стародубец Михаил
- Закревский Роман

#### Задачи, выполненные Стародубец Михаилом

- Frontend:
   - Базовая архитектура приложения.
   - Backend-шаблон HTML страницы вывода всех заметок, с возможностью перехода к конкретной заметке при клике на нее. 
 - Backend:
   - Базовая архитектура приложения, подключение необходимых модулей.
   - Роут GET `/`, который будет возвращать главную HTML страницу со всеми заметками.
   
- Frontend:
   - Backend-шаблон HTML страницы создания заметки.
   - Отправка POST запроса на сервер с созданием заметки. После ответа сервера пользователь должен быть перенаправлен на главную страницу.
   - Backend-шаблон HTML страницы детального отображения заметки. На этой странице должна быть возможность отредактировать и удалить заметку.
   - Отправка PUT запроса на сервер с отредактированной заметкой. После ответа сервера пользователь должен быть перенаправлен на главную страницу.
   - Отправка DELETE запроса на сервер для удаления заметки. После ответа сервера пользователь должен быть перенаправлен на главную страницу.
 - Backend:
   - Роут GET `/notes`, который будет отдавать HTML страницу с формой создания заметки.
   - Роут GET `/notes/${id}`, который будет отдавать HTML страницу детального отображения заметки.
   - Роут POST `/api/notes` для создания заметки.
   - Роут PUT `/api/notes/${id}` для редактирования заметки.
   - Роут DELETE `/api/notes/${id}` для удаления заметки.
   
#### Задачи, выполненные Закревским Романом

- Frontend:
   - Бекенд-шаблон HTML страницы создания списка.
   - Отправка POST запроса на сервер с созданием списка. После ответа сервера пользователь должен быть перенаправлен на главную страницу.
   - Backend-шаблон HTML страницы детального отображения списка. На этой странице должна быть возможность отредактировать и удалить список.
   - Отправка PUT запроса на сервер с отредактированным списком. После ответа сервера пользователь должен быть перенаправлен на главную страницу.
   - Отправка DELETE запроса на сервер для удаления списка. После ответа сервера пользователь должен быть перенаправлен на главную страницу.
 - Backend:
   - Роут GET `/lists`, который будет отдавать HTML страницу с формой создания списка.
   - Роут GET `/lists/${id}`, который будет отдавать HTML страницу детального отображения списка.
   - Роут GET `/api/lists/${id}` отображения заметки со списком.
   - Роут POST `/api/lists` для добавления нового списка задач с учетом того, что количество позиций в списке - не ограничено и заранее не известно.
   - Роут PUT `/api/lists/${id}` для редактирования списка задач.
   - Роут DELETE `/api/lists/${id}` для удаления заметки со списком.
   
- Стилизация проекта.
- README.md