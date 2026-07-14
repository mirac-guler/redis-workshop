# Redis Workshop
> 📚 University workshop material prepared for the Database Systems course at SRH Berlin University of Applied Sciences.

A university workshop introducing Redis, key-value databases, Docker, and RedisInsight through both theoretical concepts and hands-on demonstrations.

---

## 📖 About

This repository contains the presentation and supporting materials prepared for a university workshop on Redis.

The workshop covers the fundamentals of key-value databases, explains how Redis achieves its high performance, introduces its most commonly used data structures, and demonstrates practical use cases through live examples.

---

## ✨ Highlights

- Introduction to SQL vs NoSQL
- Understanding Key-Value Databases
- Redis Architecture
- In-Memory Storage
- Persistence (RDB & AOF)
- Redis Data Structures
- Time Complexity (O(1) & O(log N))
- Real-world Redis Use Cases
- Docker Setup
- RedisInsight
- Live Leaderboard Demonstration

---

## 🛠 Technologies

- Redis
- Docker
- RedisInsight

---

## 📄 Presentation

The complete workshop presentation is included in this repository.

Topics covered include:

- Database fundamentals
- Key-value stores
- Redis architecture
- Redis persistence
- Redis data structures
- Performance characteristics
- Practical use cases
- Live demonstrations

---

## 🚀 Getting Started

To run Redis locally using Docker:

```bash
docker run -d --name redis-server -p 6379:6379 redis
```

After the container starts, connect using:

- Redis CLI
- RedisInsight

---

## 💻 Example Commands

```redis
SET username "mirac"

GET username

DEL username
```

Example Sorted Set:

```redis
ZADD leaderboard 100 Alice
ZADD leaderboard 250 Bob

ZRANGE leaderboard 0 -1 WITHSCORES
```

---

## 📚 Repository Purpose

This repository was created as a learning resource accompanying a university workshop. Its purpose is to provide an accessible introduction to Redis concepts, practical examples, and deployment using Docker.

---

## 📜 License

Released under the MIT License.

## 🤝 Acknowledgements

This workshop was prepared as part of the Database Systems course at SRH Berlin University of Applied Sciences.
