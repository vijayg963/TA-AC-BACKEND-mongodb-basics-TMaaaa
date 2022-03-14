writeCode

Write command to

- List collections from a database.

```js
// show collections
```

- create a new collection in your country database which you created recently.

```js
// use india
// db.createCollection('delhi')
// show collections
```

Write code to for mongo:-

- crate a database named `weather`

```js
// use wether
```

- create a capped collection named `temperature` with maximum of 3 documents and try inserting more than 3 to see the result.

```js
// db.createCollection('tempertaure',{capped: true, size: 1024, max:3})
// db.tempertaure.insertMany([{delhi:34}, {mumbai: 32}, {chennai:45}]);
// db.tempertaure.find()
// db.tempertaure.insert({dharamsala:23})
// first 0ne is deleted by default as new is added.
```

- create a simple collection named `humidity`

```js
// db.createCollection(`humidity`)
```

- check whether `temperature` collection is capped or not ?

```js
// db.tempertaure.isCapped()
//  db.humidity.isCapped()
```

- Delete `humidity` collection and then the entire database(weather).

```js
//  db.humidity.drop()
// db.dropDatabase()
```
