# Соціальна мережа для спілкування та обміну контентом
---
## 1. Мета створення проєкту

Метою проєкту SocialMedia є створення повноцінної мобільної соціальної мережі, яка дозволяє користувачам спілкуватися, ділитися публікаціями, знаходити друзів та обмінюватися повідомленнями.
Проєкт був створений для практичного вивчення сучасних технологій розробки мобільних застосунків та веб-сервісів

##### Під час роботи над проєктом учасники отримали досвід у:

- розробці клієнт-серверної архітектури;
- роботі з PostgreSQL;
- реалізації JWT авторизації;
- створенні системи чатів;
- роботі з React Native та Expo;
- використанні Git та GitHub для командної роботи
---
## 2. Склад команди
- Бояркіна Орина(TEAMLEAD)/Boiarkina Oryna(TEAMLEAD) - [GitHub](https://github.com/BoiarkinaOryna/SocailMedia)
- Нікіта Годований/Nikita Hodovanyj - [GitHub](https://github.com/Nikita-Hodovanyj/Social-Network-Application-)
- Віктор Пілат/Viktor Pilat - [GitHub](https://github.com/VictorPilat/Social-Network-Application)
---
## 3. Зміст
1. [Мета створення проєкту](#1-мета-створення-проєкту)
2. [Склад команди](#2-склад-команди)
3. [Перелік модулів та технологій](#4-перелік-модулів-та-технологій)
4. [Запуск проєкту](#5-запуск-проєкту)
5. [Структура проєкту](#6-структура-проєкту)
6. [Опис модулів](#7-опис-модулів)
7. [Висновок](#8-висновок)
---

# 4. Перелік модулів та технологій

## Frontend

* React Native
* Expo
* Expo Router
* TypeScript
* Socket.IO client

## Backend

* Node.js
* Express.js
* JWT Authentication
* Socket.IO
* bcrypt

## База даних

* PostgreSQL
* Prisma ORM

## Інструменти

* Git
* GitHub
* Postman
* VS Code

---

# 5. Запуск проєкту

## Клонування репозиторію

```bash
git clone https://github.com/BoiarkinaOryna/SocailMedia.git
cd SocailMedia
```

## Встановлення залежностей Frontend та запуск
```bash
cd frontend
npx expo install
npx expo start
```

## Встановлення залежностей Backend та запуск

```bash
cd backend
npx i
npm run start
```

## Налаштування бази даних

Створити PostgreSQL базу даних та вказати параметри підключення у файлі `.env`.

Приклад:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/socialmedia
JWT_SECRET=secret_key
PORT=3000
```
---
# 6. Структура проєкту

## Frontend

```text
frontend
│
├── assets
│
├── src
│   ├── app
│   │   ├── auth
│   │   ├── chats
│   │   ├── friends
│   │   ├── settings
│   │   ├── (main)
│   │   └── (publications)
│   │
│   ├── modules
│   │   ├── auth
│   │   ├── chats
│   │   ├── friends
│   │   ├── publication
│   │   └── settings
│   │
│   └── shared
│       ├── api
│       ├── ui
│       ├── utils
│       ├── constants
│       ├── types
│       ├── icons
│       └── images
```

---

# 7. Опис модулів
## Авторизація
* реєстрація
* логін
* JWT токени
## Профіль користувача
* редагування профілю
* аватар
* інформація користувача
## Друзі
* додавання друзів
* підтвердження запитів
* список друзів
## Пости
* створення постів
* перегляд стрічки
* взаємодія з контентом
## Чати
* повідомлення в реальному часі
* приватні чати
* групові чати
* live updates через Socket.IO

---

# 8. Висновок

У результаті виконання проєкту було створено повноцінний прототип соціальної мережі з підтримкою авторизації, профілів користувачів, системи друзів, публікацій та чатів.

## Команда отримала досвід у:
* роботі з Node.js та Express;
* використанні Socket.IO для real-time комунікації;
* створенні мобільного застосунку на React Native;
* роботі з PostgreSQL та Prisma;
* організації клієнт-серверної архітектури;
* командній розробці через GitHub


## У майбутньому проєкт може бути розширений шляхом додавання:
* темної/світлої теми інтерфейсу;
* відеодзвінками;
* документація api;
* поглиблення логіки персоналізації постів та друзів;
* мобільним релізом у App Store та Google Play

---

# English Version


# Social network for collating and sharing content
---
## 1. Meta about the project

The goal of the SocialMedia project is to create a full-fledged mobile social network that allows users to communicate, share publications, find friends and exchange messages.
The project was created for practical study of modern technologies for developing mobile applications and web services

##### While working on the project, participants gained experience in:

- developing client-server architecture;
- working with PostgreSQL;
- implementing JWT authorization;
- creating a chat system;
- working with React Native and Expo;
- using Git and GitHub for teamwork
---
## 2. The composition 
- Бояркіна Орина(TEAMLEAD)/Boiarkina Oryna(TEAMLEAD) - [GitHub](https://github.com/BoiarkinaOryna/SocailMedia)
- Нікіта Годований/Nikita Hodovanyj - [GitHub](https://github.com/Nikita-Hodovanyj/Social-Network-Application-)
- Віктор Пілат/Viktor Pilat - [GitHub](https://github.com/VictorPilat/Social-Network-Application)
---
## 3. Table of Contents
1. [Project Purpose](#1-Project-Purpose)
2. [Team Composition](#2-Team-Composition)
3. [List of Modules and Technologies](#4-List-of-Modules-and-Technologies)
4. [Project Launch](#5-Project-Launch)
5. [Project Structure](#6-Project-Structure)
6. [Module Description](#7-Module-Description)
7. [Conclusion](#8-Conclusion)
---

# 4.List of modules and technologies

## Frontend

* React Native
* Expo
* Expo Router
* TypeScript
* Socket.IO client

## Backend

* Node.js
* Express.js
* JWT Authentication
* Socket.IO
* bcrypt

## База даних

* PostgreSQL
* Prisma ORM

## Інструменти

* Git
* GitHub
* Postman
* VS Code

---

# 5. Project Launch

## Cloning a repository

```bash
git clone https://github.com/BoiarkinaOryna/SocailMedia.git
cd SocailMedia
```

## Installing Frontend dependencies and running
```bash
cd frontend
npx expo install
npx expo start
```

## Installing Backend Dependencies and Running


```bash
cd backend
npx i
npm run start
```

## Database settings

Create a PostgreSQL database and specify connection parameters in the `.env` file.

Example:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/socialmedia
JWT_SECRET=secret_key
PORT=3000
```
---
# 6. Project Structure

## Frontend

```text
frontend
│
├── assets
│
├── src
│   ├── app
│   │   ├── auth
│   │   ├── chats
│   │   ├── friends
│   │   ├── settings
│   │   ├── (main)
│   │   └── (publications)
│   │
│   ├── modules
│   │   ├── auth
│   │   ├── chats
│   │   ├── friends
│   │   ├── publication
│   │   └── settings
│   │
│   └── shared
│       ├── api
│       ├── ui
│       ├── utils
│       ├── constants
│       ├── types
│       ├── icons
│       └── images
```

---

# 7. Module Description
## Authorization
* registration
* login
* JWT token
## User profile
* profile editing
* avatar
* informations user
## Friends
* adding friends
* confirmation of requests
* friend list
## Posts
* creating posts
* watching the tape
* interaction with content
## Chats
* real-time messaging
* private chats
* group chats
* live updates via Socket.IO

---

# 8. Conclusion

As a result of the project, a full-fledged prototype of a social network was created with support for authorization, user profiles, a friends system, publications, and chats.

## The team gained experience in:
* working with Node.js and Express;
* using Socket.IO for real-time communication;
* creating a mobile application on React Native;
* working with PostgreSQL and Prisma;
* organizing a client-server architecture;
* team development via GitHub

## In the future, the project can be expanded by adding:
* dark/light interface themes;
* video calls;
* api documentation;
* deepening the logic of personalization of posts and friends;
* mobile release in the App Store and Google Play

---