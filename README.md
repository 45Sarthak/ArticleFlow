# 🚀 ArticleFlow

ArticleFlow is a modern blogging platform backend built with **Spring Boot**, designed to provide secure and scalable RESTful APIs for content publishing and user interactions. It enables users to create articles, manage profiles, follow authors, comment on posts, and favorite articles while following clean architecture principles.

---

## ✨ Features

- 🔐 JWT-based Authentication & Authorization
- 👤 User Registration & Login
- 📝 Create, Update & Delete Articles
- 💬 Comment on Articles
- ❤️ Favorite & Unfavorite Articles
- 👥 Follow & Unfollow Authors
- 📄 User Profile Management
- 🏷️ Tag-Based Article Organization
- ✅ Request Validation
- ⚠️ Global Exception Handling
- 🌐 RESTful API Design

---

## 🛠️ Tech Stack

| Technology | Description |
|------------|-------------|
| Java | Programming Language |
| Spring Boot | Backend Framework |
| MyBatis | Persistence Framework |
| Maven | Dependency Management |
| MySQL / PostgreSQL | Database |
| JWT | Authentication |
| Lombok | Boilerplate Code Reduction |
| REST APIs | Client-Server Communication |

---

## 📂 Project Structure

```
src
├── config
├── controller
├── domain
├── dto
├── exception
├── mapper
├── security
├── service
├── util
└── resources
```

---

## 🏛️ Architecture

```
                Client
                  │
             REST Request
                  │
            Spring Controller
                  │
            Business Service
                  │
           MyBatis Mapper
                  │
             Database
                  │
             JSON Response
```

---

## 📌 Core Modules

### 🔐 Authentication
- User Registration
- Secure Login
- JWT Token Generation

### 👤 User Management
- Profile Management
- Follow / Unfollow Users

### 📝 Articles
- Publish Articles
- Edit Articles
- Delete Articles
- Browse Articles

### 💬 Comments
- Add Comments
- Delete Comments
- View Discussion

### ❤️ Social Features
- Favorite Articles
- Personalized Feed
- Article Tags

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/45Sarthak/ArticleFlow.git
```

### Navigate

```bash
cd ArticleFlow
```

### Build

```bash
mvn clean install
```

### Run

```bash
mvn spring-boot:run
```

---

## 📖 API Overview

| Module | Endpoints |
|---------|-----------|
| Authentication | Register, Login |
| Users | Profile, Follow |
| Articles | CRUD Operations |
| Comments | Add/Delete Comments |
| Favorites | Favorite/Unfavorite Articles |
| Tags | List Tags |

---

## 🎯 What I Learned

Through this project, I gained hands-on experience with:

- Spring Boot Application Development
- Layered Architecture
- REST API Design
- JWT Authentication
- MyBatis Integration
- Exception Handling
- Input Validation
- Database Relationships
- Clean Code Practices

---

## 🔮 Future Enhancements

- 🔍 Article Search
- 📧 Email Verification
- 🔄 Refresh Token Authentication
- 📚 Bookmarks
- 🖼️ Image Upload
- 🔔 Notifications
- 📊 Admin Dashboard
- 🌙 Dark Mode Support (Frontend)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
