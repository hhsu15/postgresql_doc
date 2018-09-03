# postgresql

## Install UI
- Download and install PSequel

## Install postgresql and run service
'''bash
- brew update
- brew doctor
- brew install postgresql
- brew services start postgresql
'''

## Create database
'''bash
- createdb 'test'  
- psql 'test' # go into the query mode and start writing command
- CREATE TABLE users(name text, age smallint, birthday date);
- \d #show the table
- \q #to exit
'''

## Bacis commands
'''bash
- INSERT INTO users(name, age, birthday) VALUES ('Hsin', 38, '1979-12-31');
- ALTER TABLE users ADD score smallint;
- UPDATE users SET score = 50 WHERE name='Hsin';
'''



