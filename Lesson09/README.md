指定抽出字段
===========

## 知识点

* db.[collection_name].find({}, {field1: true, field2: 1})

## 实战演习

~~~bash
$ mongo
> use komablog;
> db.posts.find();
> db.posts.find({}, {title:true, rank:1});
> db.posts.find({}, {title:true, rank:1, _id:0});
~~~

## 