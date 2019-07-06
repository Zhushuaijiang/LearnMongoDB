操作集合（Collection）
=====================

## 知识点

* MongoDB数据集合的操作

## 实战演习

~~~bash
$ mongo
> show dbs;
> use komablog;
> show collections;
> db.createCollection("users");
> show collections;
> db.users.renameCollection("staff"); // users -> staff
> show collections;
> db.staff.drop();
> show collections;
> db.dropDatabase();
> show dbs;
~~~

## 