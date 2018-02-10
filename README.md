### Hospital-Resident Matching Service System

#### Prerequisites

- MySQL
- Node.js

#### Configuration
Assuming Node and MySQL has been installed, MySQL server started and the `root` password set according
to `app/connection.js`, connect to the server by running the command below and entering the password

```
mysql -uroot -p
```

Then create the database and exit:
```
mysql> create database cs304project;

mysql> exit
```

To initialize the database, make sure `require('./init-db.js')` is not commented out in `app/server.js`.
To not seed the database or stop adding more rows to tables with an auto increment primary key, comment out `require('./seed-db.js')` in `app/init-db.js`.
#### Launching the app

```
node app/server.js
```

Log in at http://localhost:1234 by using the right accounts in `app/seed-db.js` or by signing up.

![screen shot 2018-02-05 at 10 55 02](https://user-images.githubusercontent.com/18509246/36058575-e06f081e-0dd8-11e8-8aaf-1f931f000bc3.png)
![screen shot 2018-02-05 at 10 55 44](https://user-images.githubusercontent.com/18509246/36058577-f2bef6e6-0dd8-11e8-9f70-bc9486ca4490.png)
![screen shot 2018-02-05 at 10 56 18](https://user-images.githubusercontent.com/18509246/36058584-26dd1d90-0dd9-11e8-8a1a-07becc4e30dc.png)
![screen shot 2018-02-05 at 10 56 55](https://user-images.githubusercontent.com/18509246/36058585-29e47a6a-0dd9-11e8-8af9-f2fcc7c00a62.png)
![screen shot 2018-02-05 at 10 57 38](https://user-images.githubusercontent.com/18509246/36058586-2ba9463c-0dd9-11e8-91c1-44ba52180930.png)
