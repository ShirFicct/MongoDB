## connnect to container

```sh
docker-compose exec mongodb bash
```

##cpnnnet  with  mongosh
```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://gutierrezshirley72:admin123@mongodb.g3vtk.mongodb.net/"
```
```sh
show dbs
show collections
```
```sh
use("platzi_store");
db.productos.find();
```
