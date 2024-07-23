## Conectarse a contenedor en docker
docker-compose exec mongodb bash

## Generar la conexión a la BD
mongosh "mongodb://marcoadmin:admin@localhost:27017/?tls=false"

## Instrucciones
showdbs -- muestra BD
show collection -- Muestra las colecciones
use ("x") -- Especificar que BD usar
