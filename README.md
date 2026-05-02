# 🐈 LazyCatBot — Твой помощник в мире Sirus.su
Автоматизируйте отслеживание прогресса вашей гильдии и игроков. Получайте красивые отчеты об убийствах боссов прямо в Discord!
---
## 🚀 Быстрый старт
### 1. Добавление бота
Чтобы добавить бота на свой сервер, перейдите по ссылке ниже и выберите нужный сервер:
👉 **[ДОБАВИТЬ LAZYCATBOT НА СЕРВЕР](https://discord.com/oauth2/authorize?client_id=1493704685297602731&permissions=277092879552&integration_type=0&scope=bot+applications.commands)**
> **Важно:** Для корректной работы боту требуются права на чтение сообщений, отправку сообщений и вставку ссылок (Embed Links).
### 2. Настройка канала
1. Создайте текстовый канал (например, `#raid-alerts`).
2. В этом канале введите команду `/set id_гильдии`.
   * *Например:* `/set 1234`
3. Бот сразу начнет мониторинг! Если бот начал отправлять килы гильдии за текущее кд, значит все ок и бот работает.
---
## ✨ Возможности
### 📊 Красивые отчеты об убийствах
Бот присылает детальный отчет сразу после убийства босса. В отчете указаны время, сложность и основные данные боя.
![Вид сообщения](https://private-user-images.githubusercontent.com/16744697/586746136-2e819cb6-afa7-4b7a-8ba2-b5de211eeb18.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Nzc3Mjg2NTEsIm5iZiI6MTc3NzcyODM1MSwicGF0aCI6Ii8xNjc0NDY5Ny81ODY3NDYxMzYtMmU4MTljYjYtYWZhNy00YjdhLThiYTItYjVkZTIxMWVlYjE4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNTAyVDEzMjU1MVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTc1NDM0MjQ1ZWQ0NGIwZDY4YTNkZDFmMzU1MmNjNTVlNTQ4YzRmMzQ4NDU2ZjExMWZmNjIxYzI5NDZjNjlhYzQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.nLe4TOJUYoiO6L15FHtH1mD5k68x0JE9fIZHzW84K18)
### 🏆 Списки лучших игроков
Следите за эффективностью ваших рейдеров. Бот формирует рейтинги по DPS и HPS для каждого сражения.
![Рейтинги игроков](https://private-user-images.githubusercontent.com/16744697/586746137-191fe178-a133-4347-b8f2-986b3369b0c9.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Nzc3Mjg2NTEsIm5iZiI6MTc3NzcyODM1MSwicGF0aCI6Ii8xNjc0NDY5Ny81ODY3NDYxMzctMTkxZmUxNzgtYTEzMy00MzQ3LWI4ZjItOTg2YjMzNjliMGM5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA1MDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNTAyVDEzMjU1MVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY4NmJjZjA4YjZjOGJiMDQ2YTFjYjI3ZWRkNTIxNTgxM2FhMGU2NDUyODY4MWIwNzUxMzBlYTA0MjllYjVmNjgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.jQ-3VyUWdqtWohqv5QZzHTvjl9CVFKRDudGUPsuDcdg)
---
## 🛠️ Команды бота
| Команда | Описание |
| :--- | :--- |
| `/set ID` | Подписаться на отчеты гильдии в текущем канале |
| `/unset ID` | Удалить подписку гильдии в текущем канале |
| `/setcat ИМЯ` | Подписаться на отчеты конкретного игрока |
| `/list` | Показать список всех подписок в канале |
| `/help` | Справка по командах и ссылка на поддержку |
больше комманд можно посмотреть в самом боте, введите / в текстовом канале дискорда куда добавлен бот
---
## ❓ Часто задаваемые вопросы
**Где взять ID гильдии?**
1. Зайдите на сайт [Sirus.su](https://sirus.su).
2. Найдите свою гильдию в базе данных.
3. ID — это число в конце ссылки. Например, в ссылке `sirus.su/base/guild/x3/1234` ID будет `1234`.
**Бот не присылает отчеты, что делать?**
Проверьте, есть ли у бота права на просмотр данного канала и на отправку сообщений (Embed). Также убедитесь, что вы использовали команду `/set` именно в том канале, куда должны приходить отчеты.
