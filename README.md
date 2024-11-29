## Run docker file: `docker-compose -f filename.yml up -d`

**Example: docker-compose -f postgresql.yml up -d**

---

## Table of Contents

- [MySql & PhpMyAdmin](#mysql--phpmyadmin)
- [Postgresql & pgAdmin4](#postgresql--pgadmin4)
- [MongoDB & MongoExpress](#mongodb--mongoexpress)

---

## Command list

| Command                                           |              To Do               |
| :------------------------------------------------ | :------------------------------: |
| docker ps                                         |      View list of Container      |
| docker exec -it container_id bash                 | Access to Docker Container by ID |
| exit                                              | Exit accessing Docker Container  |
| psql -h localhost -U POSTGRES_USER -d POSTGRES_DB |       Login to Postgresql        |

---

> ### MySql & PhpMyAdmin:

| Key      |         Value         |
| :------- | :-------------------: |
| Hosting  | http://localhost:8090 |
| username |         root          |
| password |       password        |

---

> ### Postgresql & pgAdmin4:

| Key      |         Value         |
| :------- | :-------------------: |
| Hosting  | http://localhost:5050 |
| username |    admin@admin.com    |
| password |         admin         |

- Create Server information

**Name: `db (optional)`**</br>
**Host name/address: `172.18.0.2` (check To get Host name/address below)**</br>
**Username: `postgresql`**</br>
**Password: `123`**

- To get Host name/address

**View docker container list: `docker ps`**</br>
**Check detail container: `docker inspect CONTAINER_ID`**</br>
**Check IPAddress: `NetworkSettings/Networks/IPAddress`**

---

> ### MongoDB & MongoExpress:

| Key      |         Value         |
| :------- | :-------------------: |
| Hosting  | http://localhost:8081 |
| username |         root          |
| password |         root          |
