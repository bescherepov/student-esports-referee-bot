# Student Esports Referee Bot (SERB)
## Введение
Приложение, решающее специфическую задачу некоторой студенческой киберспортивной организации, позволяющее:
1. Вести учёт турниров организации
2. Вести учёт матчей с возможностью назначения судьи и отслеживания статуса матча
3. Вести учёт выдачи призов призёрам турниров

Разрабатывается в основном в целях обучения

Приложение разрабатывается по клиент-серверной архитектуре

### Технологический стек
**Клиент**: Vue 3, Tailwind, PrimeVue, Vite

**Сервер**: Flask, EdgeDB

## Установка
### Предустановка
*TODO инструкция по установке пакетов*

Предварительно нужно установить **npm**, **edgedb**, **python:flask**, **python:flask_cors**

### Клиент
1. Зайти в папку **frontend**
2. Выполнить команду
`npm run dev`
3. После этого будет выполнена сборка и запуск клиента приложения в среде разработки. 

Чтобы приложение могло получить тестовые данные от сервера, необходимо выполнить операции пункта **Сервер**


Для отдельной сборки приложения используется команда
`npm run build`


Для предпросмотра клиента используется команда
`npm run preview`

### Сервер (установка на Linux)
1. Зайти в папку **backend**
2. Выполнить команды (рекомендуется использовать python3.12)
```bash
python -m venv .env
source .env/bin/activate
pip install Flask Flask-Cors
python app.py
```
3. После этого запустится серверная часть приложения 






