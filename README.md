# webform

# JsonPowerDB 
### You can fork it if you want. But before doing that, please give a star (It's totally free).

[Documentation Link](http://login2explore.com/jpdb/docs.html)

## "This project is all about basics of JsonPowerDB (JPDB) and how to use JPDB for CRUD operations.CRUD operations are Creating , Reading , Updating and Deleting data." 

### If you want to make changes in this repo, then create a pull request. I will be happy to add more into it. Thanks.!
### About JsonPowerDB:

- JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.
![im1](https://user-images.githubusercontent.com/70138609/203982200-f54d6630-883a-4439-a645-36be5cf3f73e.jpeg)

![im2](https://user-images.githubusercontent.com/70138609/203982227-1c8380ad-e827-4bd1-adc8-49812d0a885d.jpeg)
## Benefits of using PowerDB

 -JsonPowerDB (JPDB) is Next Generation, Creative and Disruptive Multi-mode DBMS_ with many USPs.
 
 -Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.
 
 -Serverless support for faster development - A UI developer can develop complete dynamic application.
 
 -DBMS with built in web / application server and embedded caching makes the performance lightning fast.
 
 -Server side Native NoSQL - best query performance.
 
 -In-built support to query on multiple JPDB databases.
 
 -Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.
 
 -Schema free - easy to develop and maintain.
 
 -Web-services API - Can be used with any programming language that has support for HTTP.
 
 -Enriched by a pluggable API Framework - A developer can develop a pluggable API and plugin into any of our cloud JPDB instance.
 
 -Standardisation of API development framework makes the development process easy, more readable, and less error prone.
 
 -Multiple security layers.
 
 -Nimble, Simple to use, In Memory, Real-time DBMS.
 ## Release Notes
 v0.3.2.20220829.2828 beta
 
 https://login2explore.com/jpdb/#collapse-jpdb-release-note17

 0.3.2 / 2022-08-29
 ==================
* Completed Phase-4 of Pluggable API framework for configuration properties that controls the usage of API for global and individual users.
* Added NEW pluggable API for importing data from CSV files.
* Modified existing Drive API to support the Phase-4 of Pluggable API release.
* Development for Phase-1 for Replication of user's database - Replica Manager Dashboard, Sync user database from MasterNode to ReplicaNode(s) completed. 
* Added: New methods in jpdb-commons.js (0.0.4 and 0.0.5) for creating the 
  COPY COLUMN request i.e. createCopyColumnRequest(token, jsonObj, dbName, relName), 
  RENAME COLUMN request i.e. createRenameColumnRequest(token, jsonObj, dbName, relName), 
  REMOVE COLUMN request i.e. createRemoveColumnRequest(token, jsonObj, dbName, relName), 
  CHANGE COLUMN request i.e. createChangeColumnTypeRequest(token, jsonObj, dbName, relName), 
  UPDATE RECORD request i.e. createUPDATERecordRequest2(token, jsonObj, dbName, relName).
* Improved: Documentation
* Improved: SMTP Implementation for sending Emails 
* Fixed: Various Important bugs fixed
                                    
