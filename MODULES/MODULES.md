+ architektura, usługi, domeny porty, docker
+ kod: nodejs, python, php
+ logika biznesowa - apicqrs, określenie zadań
+ apidsl - implementacja, strumieniowanie zadań

Możliwość użycia camel-a
# docker-compose.yaml

Layers:
+ user management: ldap,..
+ filesystem : sftp, webdav 21
+ DB: mariadb, sql, 3306
+ API: 8081,8082,8083
+ Server: 80

Serwery API/DB Tables:
+ readock www server

Processing:
+ ocr API
    + from pdf to json
+ files API
    + from pdf to img

Sqlite:
+ transactions API
    + aftermarket
    + premium
    + ovh
+ payments API
    + wise
    + paypal
+ invoices API
    + bought
    + sold

Server nodejs pokazujący pliki przez http
+ json
+ pdf
+ image
  update plików w bazie danych, w files


