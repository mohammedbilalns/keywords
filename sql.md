# Database 
## DBMS 
### RDBMS
#### Adavantages 
ensure acid, structured format , uses sql , data consistency through normalizatin 
## Entities and relationships 
one to one , one to many , many to many 
## Schema 
namespace 
## Three schema architecture 
external , internal and conceptual 
# Postgresql

## Advantages 
advanced queriew like window functons , common table expressions , ensures acide , support various indexing methods , open source 
## ORDBMS 
## Data types 
### Numeric 
int , smallint , binint , decimal , numeric, real , double , serial , bigserial 
### Character 
char, varchar , text 
### Date and time 
date, time , timestamp , timestampz , interval 
### Boolean 
### Binary 
bytea 
### Geometric 
point , line  , circle 
### Network address
inet, cidr , macaddr 
### JSON 
json , jsonb 
### Array 
integer , text 
### uuid 
### Range 
int4rande, daterange 
### Custom Type 

# SQL
## advantages 
standardized across rdbms , simpler , support complex queries , acid 
## Terms 
statements, table , columns , rows , candidate key , primary key , super key , composite key , natural key , foreign key , query , schema, index, join , aggregation , constraint , transaction , view , stored procedure , trigger, normalization , denormalization , subquery 
## Constrains 
primary key , foreign key , unique , check , not null , default , index , serial , on delete  , on update 

# Roles 
## Types of roles 
## Role management commands 

# SQL Commands 
## DDL 
### CREATE 
create database,  table, index, view ,function , trigger , role 
### ALTER 
rename db, rename table 
### DROP 
### TRUNCATE 
### RENAME 
## DML 
### INSERT 
### UPDATE 
### DELETE 
### SELECT 
## TCL 
begin , commit , rollback , savepoint , rollback to savepoint 

# ACID Properties 
## isolation levels
read uncommitted , read commietd , repeatable read , serializalbe 
## Write ahead logging 

# Normalization 
## Normal forms 
1nf, 2nf , 3nf ,bcnf 
## advantages  disadvantages 
adv - simple, data integrity , scalability 
disadv - not suitable for read heavy , storage overhead in some cases , over complication 
# Denormalization 
## advantages and disadvantages 
adv - read perfomance , reduced joins , simple queries 
disadv - data redundancy ,low write perfomance , storage overhead 
## denormalzing techniques 

# Indexing 
## types of indexes 
unique , single column , composite index , implicit , clustered index

# Functions 
## Advantages disadvanatages of functions 
adv : reusability , easier to read , perfomance 
disadv : no modification , slow perfomance if not optimized , harder to migrate 
## Scalar functions 
## Table values functions 

# Aggregate functions 
count , sum , avg , max , min 
string_agg , array_agg 
bool_and , bool_or 
stddev , stddev_pop , sddev_samp 
variance , var_pop , var_samp 

# Clauses 
from , where , group by , having 
order by , join , limit , offset , distinct 
union , union all , with , on , using , where exists 

## Order of execution 
from > join > where > group by > having > select > distinct > order by > limit > offset 


# Operators 
## Arithmetic operators 
+, - , * , % , ^ 
## comparison operators 
>, < = , <=, <=, != 
## Logical operators 
AND , OR , NOT 
## String operators 
like , ilike , ~
## Set operators 
UNION, UNION ALL , INTERSECT , EXCEPT 

# Joins 
## Inner joins 
## Outer joins (left , right, full)
## Cross Join
## Self Join 

# Views 
## Advantages 
dynamic , simple , security , reusability 
## Types of views 
simple , complex , materialized 

# Stored procedures 
## advantages disadvantage 
adv - perfomance , reusability , security , reduced network traffic
disadv - harder to migrate , debugging complexity , scalability issues 

# Triggers 
## types of triggers based on timing 
before , after 
## types of triggers based on frequency 
row level , statment level 
## advantages and disadvantages 
adv - automation , data integrty , consistemcy 
disdv - hidden logic , perfomance overhead , complexity 

# Cursors 
## implicit an explicit cursors 
## Advantages and disadvantages 
adv - memmory efficeincy , scrollable cursors 
disadvantages - perfomance overhead , resource consumption , risk of deadlocks 

# Scaling 
## advantages and disadvantages of vertical scaling 
adv- simpler management , const effective 
disadv - single point of failure , limited scalability 
## advantages and disadvantages of horizontal scaling 
adv - high scalability , fault tolerance 
disadv - complexity , higher cost 
## Horizontal scaing techinques 
sharding , replication, clustering 

# Sql injection 
## types of injection 
classic , blind , time based , boolean based 
## prevention methods 
parametrized queres , stored procedures , input validation , least privilege principle 
