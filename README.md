# Sample mysql dump  
**db-3m.sql.tar.gz** contains 3 million records.  
`cd /tmp`  
`wget https://github.com/d3athkai/sample-mysql-dump/blob/master/db-3m.sql.tar.gz?raw=true -O db-3m.sql.tar.gz`  
`tar xfvz db-3m.sql.tar.gz`  
`mysql -u root -p -e "create database test";`  
`mysql -u root -p test --binary-mode <db-3m.sql`  
`mysql -u root -p test -e "show tables; SELECT COUNT(*) FROM sampleTable;"`  
  
# Generate more sample mysql dumps  
Proceed to http://filldb.info/dbgenerator  
