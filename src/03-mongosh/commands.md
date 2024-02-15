
# Get into  mongodb container with shell
``` sh
docker-compose exec mongodb bash
```

# Connect with mongosh

``` sh
mongosh "URL DE CONEXIÓN"
```
# MONGO COMMANDS LINE
``` sh
show dbs
show collections
```

## DENTRO DEL SSH YA DEBERIA FUNCIONAR IGUAL

```sh
use("Database")
db.collection.command()
```
