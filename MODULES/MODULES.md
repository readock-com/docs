+ architektura, usługi, domeny porty, docker
+ kod: nodejs, python, php
+ logika biznesowa - apicqrs, określenie zadań
+ apidsl - implementacja, strumieniowanie zadań

Możliwość użycia camel-a
# dockercompose.yaml

Layers:
+ user management: ldap,..
+ filesystem : sftp, webdav 21
+ DB: mariadb, sql, 3306
+ API: 8081,8082,8083
+ Server: 80

Serwery API/DB Tables:
+ readock server

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

Localhost based on sqlite
get request

send pdf
send as base64
send as image


duplicate columns
copy from Column one to another
replace value in duplciated column

update [table].[name]
set [columnname] =
(case when [columnname] like 'December 2017%'  then REPLACE([columnname], 'December 2017', '2018 December')
when [columnname] like ... then...
ELSE...
END)

