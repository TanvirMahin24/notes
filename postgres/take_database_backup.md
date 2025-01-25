## Here is command for taking backup of database in postgres

```bash
pg_dump -h 127.0.0.1 -p 5432 -U postgres -d pass -F c -b -v -f db.dump
```
