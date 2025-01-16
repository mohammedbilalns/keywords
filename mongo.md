# Basics  
## SQL vs NoSQL 
### Advantages of SQL 
predified schema , acid transactions ,vertical scalability , support for complex queries 
### Limitations of SQL 
rigid schema , difficulty in horizontal scalability 
###  Advantages and disadvantages of noSQL 
adv - flexible schema , scalability , support for various data structures 
lim - weaker consistency , limited query capability 
## Key features of Mongodb 
document oriented , horizontal scalbility , replication,indexing aggregation , clustering 
## Advantages and disadvantages of mongodb 
## BSON VS JSON 
## Terms 
namespace , document , collection , database, field , index , queuery , cursor , replica set  , sharding 
## what is schema 
## Types of noSQL databases 
document store , key value store , column family stores , graph , time series , multimodel 
## Mongo Architecture 
documents and collections , replica sets , sharding , config servers , mongodb drivers , aggregation frameworks , indexing , storage engines , administration tools 
# Data Types 
boolean, double  ,string , arrays , object , timestamp , undefined  , object id , date , regular expresssions , javascript code
## date vs timestamp 
## components of id 
timestamp , machine identifier m process identifier , counter 
# Crud Operations 
## create read write delete  documents 
insert , inserMany , find , findOne , updateMany , updateOne , deleteOne , deleteMany 
## create and delete collection 
db.createCollection , db.collectioname.drop
## create and delete users 
db.creaateUsers, db.getUsers, db.dropUser
## upsert 
## capped collections 
## pagination 
limit , skip 
## Operators 
# Aggregation 
## Aggregation stages  
match , group, project, sort, limit , skip, addFields, set, out, merge , lookup , unwind, facet , bucket , bucketAuto , merge , redact  , arrayElemAt , 
 distinct ,  bulkwrite , addtoset ,  setUnion , iscapped , exists , expr , redact
## Aggregation operators 
sum , avg, min , max , push , first , last ,split  
## conditional operators 
in , nin , ne 
## logical operators 
and or , nor 
## comparison operators 
lt , gt , eq 

## Array 
in , nin, set , unset , inc , push , pull , elemmatch , all 
## Regex 
# Joins in Mongo 
lookup 
# Transactions 
## ACID 
### single documen and multi document atomicity 
### Isolation levels and lock mechanism 
## Lock mechanism 
# Indexing 
## Advantages and disadvantages of indexing 
## Types of indexing 
single field , compound , multikey , text , geospatial , hashed 
## create drop index 
createIndex , dropIndex 
## covered query 
### benefits and disadvantages of convered queuery 
## TTL Indexing 
## Explain 
## Total Index size 
# Sharding and Scaling 
## Purpose 
## Key concepts 
shard , shard key , config servers , query routers 
## aadvantages and disadvantages of horizontal and vertical scaling 
## cluster 
## cap theorem 
# Replication and High Availability 
## types of replication 
master-slave , master-master , peer to peer 
## benefits of replication 
## replica sets 
## Nodes 
## Journaling 
## Heartbeat & Voting 
## CAP Theorem 
## Multi Region Cluster Setup 
# GridFS 
## file metadata 
## practical use cases 
## file storage and retrieval 
# Optimisation 
## denormalisation 
## normalisation 
## best practices for query perfomance 
# Advanced topics 
## shell 
## data modelling 
### types of data modelling 
## Backup and restore 
## journaling and recovery 
## capped collection and their uses 
## bulkwrite 



read and write concerncs 
wildcard index 
$fill
rename field 
