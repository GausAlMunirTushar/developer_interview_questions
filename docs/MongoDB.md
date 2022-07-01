---
id: MongoDB
title: MongoDB
slug: /mongodb-interview-questions
keywords: ['MongoDB']
---
### 2. What is a Document in MongoDB?
A Document in MongoDB is an ordered set of keys with associated values. It is represented by a map, hash, or dictionary. In JavaScript, documents are represented as objects:
{"greeting" : "Hello world!"}

Complex documents will contain multiple key/value pairs:
```json
{"greeting" : "Hello world!", "views" : 3}
```
### 5. What is the Mongo Shell?
It is a JavaScript shell that allows interaction with a MongoDB instance from the command line. With that one can perform administrative functions, inspecting an instance, or exploring MongoDB. 

To start the shell, run the mongo executable:

```bash
$ mongod
$ mongo
MongoDB shell version: 4.2.0
connecting to: test
>
```