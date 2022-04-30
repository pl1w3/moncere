# connect to mongodb for versioning experiment

```bash
# start a connection to the mongodb as background service
mongod --config /opt/homebrew/etc/mongod.conf --fork
```

To close the connection go to `mongosh`

```bash
mongosh
db.adminCommand({shutdown: 1})
exit
```
