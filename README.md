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



## 2. Operaciones CRUD
## 3. Esquemas y relaciones
## 4. Profundización de queries dentro de MongoDB
## 5. Python con MongoDB (opcional)
## 6. Recomendaciones para poner en producción tu cluster de Atlas
