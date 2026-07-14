# Redis Hashes

Hashes are used to store objects as field-value pairs.

## Create Hash

```redis
HSET user:1 name Mirac age 20 country Turkey
```

## Read Hash

```redis
HGETALL user:1
```
