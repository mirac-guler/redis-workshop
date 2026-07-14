# Redis Strings

Strings are the most basic Redis data type and store simple key-value pairs.

## Create

```redis
SET username "mirac"
```

## Read

```redis
GET username
```

## Delete

```redis
DEL username
```

Expected output:

```text
OK
"mirac"
(integer) 1
(nil)
```
