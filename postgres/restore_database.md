## Restore a database from a backup

```bash
pg_restore -h 127.0.0.1 -p 5432 -U postgres -d pass -v db.dump
```
