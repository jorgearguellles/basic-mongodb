# basic-mongodb

- [10+ Best MongoDB Tutorials for Beginners — Learn MongoDB Online](https://medium.com/quick-code/top-tutorials-to-learn-mongo-db-f1e52bee7445)
- [MongoDB University](https://university.mongodb.com)

## 1. Introducción

### Bases de datos NoSQL

Dentro de las bases de datos No SQL tenemos 4 grandes familias:
1. Key-values stores
  ![Key-values stores](./screenshots/key-value-stores.png)
  Son bastante usadas para guardar información en caahse, info de usuarios.
  La simpicidad de su estructura se vuelve dificil de manejar al momento de escalar.
2. Graph databases
  ![Graph-databases](./screenshots/graph-databases.png)
3. Wide-column stores
  ![wide-column-stores](./screenshots/wide-column-stores.png)
  Se caracterizas por tener dos llaves: Una llave de fila y otra llave de comunas.
  Las dos llaves nos permiten hacer queries mucho más rápidas.
4. Document databases
  ![document-databases](./screenshots/document-databases.png)
  Permiten guardar documentos (JSON) dentro de sus colecciones.

**Resumen**
![resumen](./screenshots/resumen.png)

### ¿Qué es mongoDB?, sus caracteristicas y el ecosistema.

**¿Qué es mongo DB?**
MongoDb es:
- Una base de datos no relacional (NoSQL)
- Basada en documentos (JSON -> BSON)
- Base de datos distribuida (facilmente escalable horizontal y verticalmente, muchos servidores = clouster de MongoDB)

**Caracteriticas**
- Nos permite guardar documentos en estructuras similares a las JSON, precisamente se llaman BSON
- Trabaja con schemas ( schema en NoSQL -> Colecciones en SQL) que nos permiten guardar docuemtnos que no necesariamente tengan la misma estructura
- Lenguaje explicito para realizar queries
- Codigo abierto
- Es gratis

**Ecosistema**
![Ecosistema](./screenshots/ecosistema.png)

### MongoDb Atlas

**Caracteriticas**
- Aprovisionamiento automático de clusters con MongoDB
- Alta disponibilidad
- Altamente escalable
- Seguro
- Disponible en AWS, GCP y Microsoft Azure
- Fácil monitoreo y optimización

### Lista de comandos en la termina del Mongo DB
- **use nombreDB:** Es el comando para crear una base de datos con el nombre **nombreDB**
- **db:** Es el comando para saber en que BD estoy en este monento
- **show dbs:** Es el comando para mostrar las BD existentes
- **show collections:** Es el comando para mostrar las colleciones en la BD en la que estoy trabajando

### MongoDB + Drivers

**¿Qué son los Drivers en MongoDB?**
Son librerias que utilizamos para couminar nuestra appliacaión con nuestra base de datos. Sin nuestros drivers no podemos trabajar con nuestros cluster de base de datos.

![Arquitectura](./screenshots/arquitectura-mongodb.png)

**¿Cómo agregar los drivers dentro de nuestro proyecto?**
Usamos un gestor de dependencias. Lo agregamos en nuestro gestor de dependencia;
- **Python:** ```python -m pip install pymongo```
- **Node.js:** ```npm install mongodb --save```
- **Ruby:** ```gem install mongoid```
- **GO:** ```dep ensure -add go.mongodb.org/mongo-driver/mongo```
- **Java con maven:**
```# build.gradle compile 'org.mongodb:mongo-java-driver:2.12.3'```

![CRUD](./screenshots/inicio-rapido.png)


## 2. Operaciones CRUD
## 3. Esquemas y relaciones
## 4. Profundización de queries dentro de MongoDB
## 5. Python con MongoDB (opcional)
## 6. Recomendaciones para poner en producción tu cluster de Atlas
