# JSON-Power-DB-Project

The JSONPowerDB database is a high-performance, lightweight, ajax enabled, serverless, simple-to-use, real-time database. Database applications can be developed quickly and easily without server-side programming or scripting.

In essence, it's a database server with REST API services that are developer friendly.

![image](https://user-images.githubusercontent.com/53810310/178908529-a5ae5c9c-912a-4a26-bfa0-95d8b266454f.png)

![image](https://user-images.githubusercontent.com/53810310/178908714-25d6c9ce-ebe6-47f1-aabc-5cc35e063b9f.png)

JPDB has a ready-to-use API for JSON document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

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
2. PUT METHOD --> Insert single record to the DB
3. UPDATE IN DB --> Update the data in DB
4. REMOVE IN DB --> Remove the data in DB

### GET ALL IN DB -->

```
{
    "token": "90939226|-31949288247042234|90940026",
    "cmd": "GET_ALL",
    "dbName": "Employee",
    "rel": "Emp-Rel"
}
```

In response, it will give you all the records in the database of particular relation metioned.

```
{
  "data": "{\"file_status\":\"OK\",\"total_records\":5,\"json_records\":[{\"rec_no\":1,\"record\":{\"name\":\"Harapriya Behera\",\"id\":\"001\",\"mobileno\":\"7654568764\",\"email\":\"harapriya@gmail.com\"}},{\"rec_no\":2,\"record\":{\"name\":\"Soumaya\",\"id\":\"002\",\"mobileno\":\"5679876458\",\"email\":\"smruti@gmail.com\"}},{\"rec_no\":3,\"record\":null},{\"rec_no\":4,\"record\":{\"name\":\"Priti Bhoi\",\"id\":\"004\",\"mobileno\":\"8764569876\",\"email\":\"priti@gmail.com\"}},{\"rec_no\":5,\"record\":{\"name\":\"Priti Bhoi\",\"id\":\"004\",\"mobileno\":\"8764569876\",\"email\":\"priti@gmail.com\"}}],\"total_pages\":1,\"current_page\":1}",
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

