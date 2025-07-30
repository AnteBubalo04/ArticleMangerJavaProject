# ABubaloProject

## 📘 Project Overview

**ABubaloProject** is a modular Java application developed in Apache NetBeans using Apache Maven for build and dependency management. It is structured as a multi-module project to promote reusability, maintainability, and a clean separation of concerns.

The application centers around managing articles with full database interaction and potential XML support, built on top of modern Java 20 features.

---

## ✨ Features

### 🧠 Core Functionality
- 📝 **Article Management**
  - Create, read, update, and delete (CRUD) articles
  - Business logic encapsulated in the `ArticleManager` module

- 🗃 **Data Access Layer (DAO)**
  - Abstracted database access using JDBC
  - Supports Microsoft SQL Server
  - Clean separation between logic and persistence

- ⚙️ **Utility Module**
  - Centralized helper functions
  - Includes support for XML parsing via JAXB

### 🚀 Development Features
- 📦 **Maven Multi-Module Project**
  - Modular design to isolate concerns (UI, DAO, Utilities)
  - Shared dependencies managed at the parent level

- 🔒 **Java 20 Compatibility**
  - Leverages modern Java language features

- 🔄 **XML Serialization**
  - JAXB-based serialization and deserialization support

---

## 🛠 Technologies Used

| Technology         | Purpose                                       |
|--------------------|-----------------------------------------------|
| **Java 20**        | Primary programming language                  |
| **Apache Maven**   | Build automation and dependency management    |
| **NetBeans IDE**   | Development environment                       |
| **Microsoft SQL Server** | Database system                        |
| **JDBC (mssql-jdbc)** | Database connectivity                     |
| **JAXB (jaxb-impl)**| XML data binding                             |

---

## 📂 Project Structure


