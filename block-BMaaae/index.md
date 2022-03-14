writeCode

Write code to:-

- create a database named `sports`.

```js
// use spoets
```

- list all databases present in local mongod server.

```js
// show dbs
```

- create 3 collections named `cricket`, `football`, `TT` in sports databse.

```js
// db.createCollection('cricket')
// db.createCollection('football')
// db.createCollection('TT')
```

- add multiple players in those collections which should have fields like `name`, `age` and `email` and `bid_price`.

```js
// add all the data to in mongo db shell command in a variable.
// db.circket.insertMany(players)
// db.football.insertMany(players)
// db.TT.insertMany(players)
```

- list all collections in sports database.

```js
// show collections
```

- rename `TT` collection to `tennis`.

```js
// db.TT.renameCollection('tannis')
```

- create a capped collection called `khokho` which should have max 3 documents.

```js
//  db.createCollection('khokho', {capped: true, size: 2048, max: 3})
```

Try inserting more than 3 and see what happens?

- check whether a collection is capped or not?
- drop all documents from `football` collection.
- delete cricket collection completely.
- delete sports database.
- check which database you are connected to ?
- connect to test database

```js
// db.khokho.isCapped()
// db.football.drop()
// db.cricket.drop()
// db.dropDatabase()
// db
// use test
```
