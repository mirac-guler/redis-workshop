# Redis Lists

Lists store ordered collections of elements.

## Add Elements

```redis
LPUSH tasks "Study Redis"
LPUSH tasks "Finish README"
```

## Read List

```redis
LRANGE tasks 0 -1
```

Expected output:

```text
1) "Finish README"
2) "Study Redis"
```
