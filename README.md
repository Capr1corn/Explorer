# Explorer
Explorer is a key-value storage system with client and server.   
Explorer use B+ tree as storage engine. Client and server communicate using the TCP protocol.
## Compile
make

## Example  
First, run the server program :  
./exp-srv
Then, run the client program :   
./exp-cli   
Insert   
&gt; set  zx  1  
Search  
&gt; get  zx  
Update  
&gt; update  zx  
Delete  
&gt; del  zx  
State  
&gt; stat  
Help  
&gt; h  
Quit  
&gt; q
