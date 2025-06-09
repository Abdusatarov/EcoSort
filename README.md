# EcoSort
EcoSort — проект для отображения контейнеров сортировки отходов
Проект в стадии разработки.

## Стек:
- Frontend: React, Leaflet
- Backend: Node.js, Express, MongoDB
- Авторизация, карта с контейнерами, фильтры

## Статус
⚠️ WIP — Work In Progress

markdown
# ♻️ Ecosort — карта контейнеров сортировки отходов

**Ecosort** — это веб-приложение, которое помогает пользователям находить ближайшие контейнеры для раздельного сбора мусора. Проект направлен на продвижение экологичных привычек и поддержку ответственного отношения к окружающей среде.

## 🚀 Функциональность

- 🔐 **Регистрация и авторизация пользователей**
- 📍 **Интерактивная карта** с отображением контейнеров (Leaflet + OpenStreetMap)
- 🗑️ **Фильтрация** по типу отходов (пластик, стекло, бумага и др.)
- ✅ **Добавление и редактирование контейнеров** (для админов)
- 👤 **Личный кабинет** пользователя
- 🌐 **API** на Express + MongoDB

## 🛠️ Технологии

| Раздел       | Стек                                         |
|--------------|----------------------------------------------|
| Frontend     | React, React Router, Leaflet, Axios          |
| Backend      | Node.js, Express, MongoDB (Mongoose)         |
| Аутентификация | JWT (JSON Web Token), bcrypt               |
| Прочее        | dotenv, CORS, Git, REST API                 |

## 📦 Установка проекта (локально)

### 🔧 Backend

bash
git clone https://github.com/Abdusatarov/EcoSort.git
cd ecosort/backend
npm install
npm run dev


Создай файл `.env` с переменными:


PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret


### 🖼️ Frontend

bash
cd ../frontend
npm install
npm start




