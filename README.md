# Arizona System

Restaurant staff management system - учет рабочего времени, расписание смен и внутренний чат для сотрудников ресторана.

## Стек

- Backend: Node.js, Express
- База данных: SQLite
- Авторизация: JWT + bcrypt
- Реальное время: WebSocket (ws)
- Безопасность: helmet, express-rate-limit, express-validator
- Загрузка файлов: multer

## Возможности

- JWT-авторизация с ролями (admin, manager, employee)
- Учет рабочего времени: отметка прихода/ухода, принудительная остановка смены
- Табель учета рабочего времени с экспортом
- Расписание смен сотрудников
- Групповые чаты по отделам (WebSocket, реальное время)
- Реакции на сообщения, отметка прочитано
- Поиск по сообщениям
- Заявки на переработку
- Статистика и отчеты для бухгалтера
- Загрузка аватаров

## Установка и запуск

1. Клонировать репозиторий:
   git clone https://github.com/qorievdev-cmd/arizona-system.git
   cd arizona-system

2. Установить зависимости:
   npm install

3. Запустить сервер:
   node server.js

4. Открыть в браузере: http://localhost:3000

## Автор

Ruslan Qoriev - начинающий backend-разработчик
- GitHub: https://github.com/qorievdev-cmd
- Email: qoriev.dev@gmail.com
