# Connect to container

```sh
docker exec mongodb bash
```

# Connect with mongosh

```sh
mongosh "{url}"
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=SCRAM-SHA-256&tls=false"
mongosh ""
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find();

```