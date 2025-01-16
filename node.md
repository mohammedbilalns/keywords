
# Core Modules in Node(8)
http , fs , path , url , os , events , crypto , util
## Path Module 
basename , extname , parse , format , join , isAbsolute , resolve 
## OS Module
arch , cups, freemem , totalmem , hostname , platform , release , uptime , networkinterfase 
## URL Module 
hostname , pathname , searchParams.get, resolve 
## HTTP Module and http 
### Components of HTTP Request (6)
request headers , request methods , request url, ip , path and queury params  , request body , cookie 
#### components of Request Headers(8)
 host , user-agent , connection(keep-alive, close), accept , DNT,content type ,  Priority, 
#### Different http methods(8)
get, post , put , patch , delete ,head , options , trace
##### Idempotencies 
#### Getting body from buffer 
### Components of HTTP Response(5)
status code , status message , response heders, response body , cookies 
#### Response status codes 
#### types  of response headers(6)
content type , content-length , set-cookie(httponly) ,secure ,cache-control , Location  
##### set-cookie response header and its configuration 
## HTTPS
## File System Module
### Sync , Async , Promise Methods(7)
readFile, writeFile , appendFile , unlink, mkdir, rmdir ,readdir , stat 
### Streams 
#### Different types of stream 
#### Stream Piping 
#### stream methods
createReadStream , createWriteStream
### Buffer
#### Buffer Methods 
Buffer.alloc , Buffer.from , Buffer.concat ,   
## Events Module
emit , on 
## DNS
dns.lookup , dns.resolve , dns.reverse , dns.gerservers , dns.setServers 

## child_process
### Fork vs spawn 
### exec vs execFile 
# NPM 
### npm vs npx 
### package.json vs package.lock
package.json - author ,name , description , version , scripts , engines , dependencies , devdependencies
#### Dependencies Dev Dependencies 
#### NPM Scripts 
# Event driven architecture in nodejs
event emitter, listner and handler 
## Libuv
### Components of Libuv (5)
event loop , asynchronous I/O , Thread Pool , child processes , timers 
#### Event loop 
#### Process.nextTick 
#### setImmediate 
#### I/O Pooling 
### thread pool 
#### thread 
# Clustering in node 
## Key features 
## Methods
fork , isMaster , isWorker, on , workers 
## Benefits 
# Worker threads
## cluster vs child process vs worker threads 
## cluster vs worker 






thresholding 
