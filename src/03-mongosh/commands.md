## Connect to container

```sh
docker compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://sebadmin:sebadmin123@mongodb101.ps30pn2.mongodb.net/test"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```