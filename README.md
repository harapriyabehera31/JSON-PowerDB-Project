# JSON-Power-DB-Project

JSONPowerDB is a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database. Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.

It is basically a Database Server with Developer friendly REST API services.

JPDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

Documentation Link --> https://login2explore.com/jpdb/docs.html#jpdb-command-request

### Benefits Of Using JSONPowerDB:
- It is realtime and simple to use.
- Easy to maintain the reconds.
- Serverless support - fast development - cuts time to market.
- Build using world's fastest indexing engine PowerIndex which gives unlimited data capacity, supporting unlimited indexes, realtime data processing which makes it fast and secure.
- Give developer friendly Webservices API which reduce the developement cost.
- Multiple Security Layers.
- Schema free - easy to maintain
- A single instance - Million Indexes
- Inbuilt support for querying multiple databases.
- It is light weight.
- It is a serverless database so that you don't have to choose an instance size at all.

### Use cases:
- All RDMS use cases.
- All key-value use cases.
- All document use cases.
- Time series/geospatial analytics.
- Real time application for data analytics.
- Live working HTML templates.
- Any software application that needs backend DB. (Dynamic web-apps/Mobile/Desktop Apps)

## Project Breakdown :

In this project, I create 6 methods to play with JSONPowerDB.

1. GET ALL IN DB --> Get all records in DB
2. GET BY KEY --> Get your desired data by inputting the key name
3. GET BY RECORD --> Get data by putting the record number
4. PUT METHOD --> Insert single record to the DB
5. UPDATE IN DB --> Update the data in DB
6. REMOVE IN DB --> Remove the data in DB

### GET ALL IN DB -->

```
{
    "token": "608862679|6881615563234464505|608862542",
    "dbName": "INDORE-TERAPANTH-DIRECTORY",
    "cmd": "GET_ALL",
    "rel": "MEMBERS-FAMILY",
    "pageNo": 1,
    "pageSize": 5,
    "createTime": true,
    "updateTime": true
}
```

In response, it will give you all the records in the database of particular relation metioned.

```
{
  "data": "{\"file_status\":\"OK\",\"total_records\":4,\"json_records\":[{\"rec_no\":1,\"created\":1656865732294,\"record\":{\"password\":\"1234\",\"name\":\"Harsh\",\"id\":\"3\",\"mobileno\":\"9967025671\",\"email\":\"harsh@gmail.com\",\"mark\":100},\"updated\":1656865732294},{\"rec_no\":2,\"created\":1656866471493,\"record\":{\"name\":\"Indrajit Sahu\",\"id\":\"2\",\"mobileno\":\"1064728030\",\"email\":\"ind7@gmail.com\"},\"updated\":1656866471493},{\"rec_no\":3,\"created\":1656866541343,\"record\":null,\"updated\":1656866541343},{\"rec_no\":4,\"created\":1656866688123,\"record\":null,\"updated\":1656868402835}],\"total_pages\":1,\"current_page\":1}",
  "message": "DATA RETRIEVED FROM PI",
  "status": 200
}
```

All the records will be shown accordingly.

### PUT Method to Insert Data -->

By PUT method, we can create/insert data in to the database, either it will be row or coloumn, data can be insert multiple times.

With this you can create the databases and relations. 

### UPDATE IN DB -->

In UPDATE, we can modify the existing records in the databases.

Here, we can update multiple records in the database or add a new column in a record.

### REMOVE IN DB -->

By this REMOVE method, we can remove the entire record from the relation with just the record number.

-----------------------------------------------------------------------------------------------------------------------------------------
