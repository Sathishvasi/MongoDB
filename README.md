# MongoDB Configurations & Basic CRUD Operations 



MONGODB SERVER CONFIGURATION

1. Install MongoDB from official site 
-> URL(https://www.mongodb.com/download-center?jmp=nav#community)



2. After Installation Set your System Environment variables as MongoDB path
   
   MongoDB path at system -> (C:\Program Files\MongoDB\Server\4.0\bin)
   

   Inside the path, Check weather "mongo.exe" available or not
   
3. Check weather MongoDB connection established
   
   * Open terminal
   
   * Type "cd ~" to change root path
   
   * Type "mongo" -> It will show mongo server & port (ex: mongodb://127.0.0.1:27017)
   * Type "showdbs" to view available database in MongoDB

MONGODB WITH NODE CONFIGURATION

1. With the use of NodeJS we can run further queries in MongoDB

2. Install NodeJS from official site

3. Open Terminal
   * npm install -g mongodb -> It installs MongoDB globally in NodeJS
   * After that packages will be added to that particular path
     PATH: (C:\Users\(System-name)\AppData\Roaming\npm\node_modules\mongodb)
   
4. Include the Files that i have uploaded in this repository 

5. Open Terminal
   * Type "node (FileName).js"
   * It will perform related operation based on query 

6. Files Included
   * node-mongodb-create-db.js 
     MongoDB will create the database if it does not exist, and make a connection to it

   * node-mongodb-create-collection.js 
     Used to create new collection in MongoDB & Collections are considered as table in database

   * node-mongodb-insert-documents.js 
     Used to insert new Documents in MongoDB & Documents are considered as row of the table

   * node-mongodb-update-documents.js 
     You can update a record, or document as it is called in MongoDB

   * node-mongodb-find-documents.js
     Used to Select particular document in the Collection

   * node-mongodb-find-document-query.js
     Used to Select particular document in the Collection through queries

   * node-mongodb-find-sort.js
     Used to select the documents in sorted order

   * node-mongodb-delete-documents.js
     Used to delete particular documents in collection

   * node-mongodb-drop-collection.js
     Used to drop the collection from database
