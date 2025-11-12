# 🌐 `blog-api` — REST API Server for a Blog Platform

> *A Node.js + Express + MongoDB backend for managing blog content — with authentication, file uploads, and tag management.*

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)  
[![Node.js Version](https://img.shields.io/badge/Node.js-%3E%3D%2018-green)](https://nodejs.org/)  
[![MongoDB](https://img.shields.io/badge/MongoDB-%3E%3D%204.0-green)](https://www.mongodb.com/)

---

## 🔍 Overview

`blog-api` is a **REST API** backend built with **Node.js, Express, and MongoDB**, designed to handle user authentication, content management, and media uploads for a blog platform. The server includes:

- **JWT-based authentication** for secure user sessions  
- **CRUD operations** for blog posts with validation  
- **File upload handling** with `multer` for image management  
- **Tag-based content discovery** for popular tags  
- **Input validation** using `Joi` for data integrity  
- **CORS support** for cross-origin requests  

This project serves as the backend for a modern blog application, emphasizing **security**, **scalability**, and **maintainability**.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Node.js (ESM) | JavaScript runtime environment |
| Express | Web framework for routing and middleware |
| MongoDB + Mongoose | NoSQL database and ODM |
| Multer | File upload middleware |
| CORS | Cross-origin resource sharing |
| JWT | Authentication and session management |
| Joi | Input validation and sanitization |

---

## 🚀 Quick Start

### Prerequisites

- **Node.js** >= 18
- **MongoDB** (local instance or MongoDB Atlas)
- A `.env` file with environment variables (see [Configuration](#-configuration))

### Setup

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd blog-api
