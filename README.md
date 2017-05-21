# Tools
- node.js
- MongoDB
- express

# How it work
## GET
 - '/lists' : see all tasks
 - '/lists/:_Id' : see one task

## POST
 - '/lists' : add your task

## DELETE
 - '/lists/:_Id' : delete one task

## PUT
 - '/lists/:_Id' : update/edit one task
 
# How to set up
1. Install [Node.js](https://nodejs.org/en/download/) and [MongoDB](https://docs.mongodb.com/manual/installation/)
2. Check installation on cmd
- node.js
```sh
node -v
v6.10.3
```
- mongoDB
```sh
mongo -version
MongoDB shell version v3.4.4
git version: 888390515874a9debd1b6c5d36559ca86b44babd
OpenSSL version: OpenSSL 1.0.1u-fips  22 Sep 2016
allocator: tcmalloc
modules: none
build environment:
    distmod: 2008plus-ssl
    distarch: x86_64
    target_arch: x86_64
```
3. clone this repository
4. install node_module on Command Prompt (Administrator) in folder repository
```sh
npm install
```
5. install express and nodemon
express will be used to create the server while nodemon will help us to keep track of changes to our application by watching changed files and automatically restart the server.
```sh
npm install --save-dev nodemon

npm install express --save
```
6. to start server
```sh
npm run start
```
7. install mongoose
```sh
npm install mongoose --save
```
8. start MongoDB server
```sh
mongod
```
9. test via [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop)
