## Run docker file: `docker-compose -f filename.yml up -d`

**Example: docker-compose -f postgresql.yml up -d**

---

> ### MySql & PhpMyAdmin:

- [Host URL](http://localhost:8090)

```php
username: root
password: password
```

---

> ### Postgresql & pgAdmin4:

- [Host URL](http://localhost:5050)

```php
username: admin@admin.com
password: admin
```

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

- [Host URL](http://localhost:8081)

```php
username: root
password: root
```
