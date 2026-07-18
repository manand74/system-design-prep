# 4-Week Hands-on System Design Preparation

A structured, project-based engineering roadmap to master large-scale system design concepts by building functional
microservices in Java.

## 🏗️ Architecture Blueprint

This repository leverages Docker Desktop to emulate production-grade infrastructure locally.

* **Cache & Rate Limiting:** Redis
* **Relational Storage:** PostgreSQL
* **Event Broker:** Apache Kafka
* **Cloud Storage:** LocalStack (AWS S3)

---

## 📅 Roadmap & Progress Tracking

### 🚀 Week 1: URL Shortener (In Progress)

* **Core Concepts:** Key-Value Stores, Consistent Hashing, Base62 Encoding, DB Sharding.
* **Tech Stack:** Java, Spring Boot, Redis, PostgreSQL.
* **Status:** ⏳ Setting up dependencies.

### 🛡️ Week 2: Distributed Rate Limiter

* **Core Concepts:** Sliding Window Log, Token Bucket, Race Conditions, Distributed Locks.
* **Tech Stack:** Java, Redis, k6 (Load Testing).
* **Status:** 🛑 Locked.

### 💬 Week 3: Real-Time Chat Application

* **Core Concepts:** WebSockets, Connection Management, Pub/Sub, Queue Architecture.
* **Tech Stack:** Java, Apache Kafka, Postman.
* **Status:** 🛑 Locked.

### 🎬 Week 4: Video Streaming Platform

* **Core Concepts:** CDNs, Video Chunking (HLS/DASH), Object Storage, Reverse Proxies.
* **Tech Stack:** Java, LocalStack (S3), NGINX, FFmpeg.
* **Status:** 🛑 Locked.

---

## ⚙️ Local Infrastructure Setup

To spin up all backend systems, ensure Docker Desktop is running and execute:

```bash
docker-compose up -d
```
