# express-tutorial
express tutorial - covering nodejs, resful api, or etc

- 코드랩 nodejs API 실습 했던 것 외.. 잡다구리?

##준비
### 노드 설치
 - https://nodejs.org   v.6.6.0
 
```
node --version
npm --version
```
   
###데이터베이스 설치
 
#####MySQL
 - Homebrew 이용
     
```brew install mysql```
- 접속

```
msyql.server start
mysql.server stop
mysql.server status
```
- password

```
mysql -u root -p
```
- 그 외
```
mysql -u root -h localhost -p 

show databases;

create database node_api;

use node_api;

show tables;

describe users;

ALTER USER 'root'@'localhost' IDENTIFIED BY 'MyNewPass';
```
