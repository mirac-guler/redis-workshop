![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

# Redis Workshop

> 📚 University workshop material prepared for the **Database Systems** course at **SRH Berlin University of Applied Sciences**.

A hands-on introduction to Redis, key-value databases, Docker, and RedisInsight through theoretical concepts and practical demonstrations.

---

## 📖 About

This repository contains the presentation and supporting materials prepared for a university workshop on Redis.

The workshop introduces the fundamentals of key-value databases, explains why Redis achieves high performance, explores its core data structures, and demonstrates practical use cases through hands-on examples.

---

## 📚 Topics Covered

- SQL vs NoSQL
- Key-Value Databases
- Redis Fundamentals
- Redis Architecture
- In-Memory Storage
- Persistence (RDB & AOF)
- Time Complexity (O(1) & O(log N))
- Redis Data Structures
- Real-world Use Cases
- Docker Setup
- RedisInsight
- Leaderboard Demonstration

---

## 🛠 Technologies

- Redis
- Docker
- RedisInsight

---

## 📂 Repository Structure

```text
redis-workshop
│
├── README.md
├── docker-compose.yml
├── screenshots/
│   ├── redis-strings.png
│   ├── redis-lists.png
│   ├── redis-hashes.png
│   └── redis-leaderboard.png
├── examples/
│   ├── strings.md
│   ├── lists.md
│   ├── hashes.md
│   └── sorted-sets.md
└── Key-Value Stores Redis Overview (1).pdf
```

---

## 📄 Presentation

The complete workshop presentation is included in this repository.

**Presentation:** `Key-Value Stores Redis Overview (1).pdf`

---

## 🚀 Quick Start

### Using Docker Compose

Run Redis locally:

```bash
docker compose up -d
```

This starts a Redis server on port **6379**.

Then connect using:

- Redis CLI
- RedisInsight

---

## 💻 Example Commands

### Strings

```redis
SET username "mirac"
GET username
DEL username
```

### Sorted Sets

```redis
ZADD leaderboard 100 Alice
ZADD leaderboard 250 Bob

ZRANGE leaderboard 0 -1 WITHSCORES
```

---

## 📚 Additional Examples

More Redis examples are available in the **examples** folder.

- Strings
- Lists
- Hashes
- Sorted Sets

---

## 🖼 Demo Screenshots

### Redis Strings

Basic key-value operations using `SET`, `GET`, and `DEL`.

![Redis Strings](screenshots/redis-strings.png)

---

### Redis Lists

Working with ordered collections using `LPUSH` and `LRANGE`.

![Redis Lists](screenshots/redis-lists.png)

---

### Redis Hashes

Storing structured objects using `HSET` and `HGETALL`.

![Redis Hashes](screenshots/redis-hashes.png)

---

### Redis Sorted Sets (Leaderboard)

Building a simple leaderboard using Redis Sorted Sets.

![Redis Leaderboard](screenshots/redis-leaderboard.png)

---

## 🤝 Acknowledgements

Prepared as part of the **Database Systems** course at **SRH Berlin University of Applied Sciences**.
