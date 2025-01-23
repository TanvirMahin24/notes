# Install MongoDB Database tools

URL: [Official Site](https://www.mongodb.com/try/download/database-tools)

# Restore MongoDB Database dump

Here is the command to restore the dump of the MongoDB database. The command will restore the dump of the database.

```bash
mongorestore --uri "mongodb+srv://<mongo_username>:<mongo_pass>@localhost:27017/db" --drop /dump/db
```

Here the `--drop` is used for dropping the existing database before restoring the dump.

## Using docker

    ```bash
    docker run --rm -v /path/to/dump:/dump mongo:latest mongorestore --uri "mongodb+srv://<mongo_username>:<mongo_pass>@localhost:27017/db" --drop /dump/db
    ```
