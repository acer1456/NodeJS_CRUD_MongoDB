# CRUD App with Node.js & MongoDB

## Tools we use 
- [Postman](https://www.getpostman.com/) (a web tool testing for our CRUD function)
- [mLab](https://mlab.com)  (a website provides free MongoDB testing enviroment)


### 1. begin
```shell
$ git clone (This Repositories)
```

### 2. Install package
```shell
$ npm install
```

#### 3. Replace the code which in app.js to connect DB
```shell
dev_db_url = 'mongodb://<DBuser>:<DBpassword>@ds255262.mlab.com:55262/mycrud';
```

### 4. Run
```shell
$ node app.js
```

### 5. Use Postman to test CRUD
```shell
Create - POST- localhost:3000/products/create
Read - GET- localhost:3000/products/5b997afbab98dd4f9e751257
Update - PUT- localhost:3000/products/5b997afbab98dd4f9e751257/update
Delete - DELETE- localhost:3000/products/5b997afbab98dd4f9e751257/delete
```


#### reference
https://codeburst.io/writing-a-crud-app-with-node-js-and-mongodb-e0827cbbdafb