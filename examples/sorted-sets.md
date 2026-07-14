# Redis Sorted Sets

Sorted Sets store unique members associated with scores.

## Leaderboard Example

```redis
ZADD leaderboard 120 Alice
ZADD leaderboard 250 Bob
ZADD leaderboard 180 Charlie
```

## Read Leaderboard

```redis
ZRANGE leaderboard 0 -1 WITHSCORES
```
