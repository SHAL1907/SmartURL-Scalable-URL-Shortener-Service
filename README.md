# 🚀 SmartURL – Scalable URL Shortener Service

## 📌 Overview
SmartURL is a backend system that converts long URLs into short, unique links and efficiently redirects users using optimized database queries and caching.

## ⚙️ Tech Stack
- Java, Spring Boot
- MySQL (Primary DB)
- Redis (Caching)
- JPA (Hibernate)

## 🔑 Features
- Generate short URLs using hashing
- Redirect to original URL
- RESTful APIs
- Optimized database queries
- Redis caching for faster response

## 📡 API Endpoints

### 1. Shorten URL
POST /api/url/shorten

Request:
{
  "originalUrl": "https://example.com"
}

Response:
{
  "shortUrl": "http://localhost:8080/abc123"
}

---

### 2. Redirect
GET /{shortCode}

Redirects to original URL

---

## ⚡ Improvements
- Add authentication (JWT)
- Add analytics (click count)
- Add rate limiting

---

## 🧠 System Design Concepts Used
- Hashing for unique keys
- Caching with Redis
- Database indexing
- Scalable API design

---

## 👩‍💻 Author
Shalini Rani
