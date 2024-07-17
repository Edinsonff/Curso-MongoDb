# Connect to conatiner

```sh
docker-compose exec mongodb bash
```
## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://edinbol123:Panda1993ff_@mongodb1.d2w4dwv.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")

db.productos.find()

```
