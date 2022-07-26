
![logo.readock.com](https://logo.readock.com/1/cover.png)

# [docs.readock.com](https://docs.readock.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/readock-com/docs/edit/main/ABOUT/MENU.md) 

+ [Blog - www.readock.com](https://www.readock.com/)
+ [Example use cases - examples.readock.com](http://examples.readock.com)
+ [Logotyp: logo.readock.com](https://logo.readock.com/)

+ [LICENSE](LICENSE)

## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/readock-com/docs/edit/main/ABOUT/ABOUT.md)



+ architektura, usługi, domeny porty, docker
+ kod: nodejs, python, php
+ logika biznesowa - apicqrs, określenie zadań
+ apidsl - implementacja, strumieniowanie zadań

Możliwość użycia camel-a
# docker-compose.yaml

## Layers:
+ user management: ldap,..
+ filesystem : sftp, webdav 21
+ DB: mariadb, sql, 3306
+ API: 8081,8082,8083
+ Server: 80

### Serwery API/DB Tables:
+ readock www server

### Processing:
+ ocr API
    + from pdf to json
+ files API
    + from pdf to img

### Data based on sql DB:

#### transactions API
    + aftermarket
    + premium
    + ovh

#### payments API
    + wise
    + paypal


#### invoices API
    + bought
    + sold

Server udostępnia pliki poprzez server Nodejs

    http -> ftp -> fs 

Backup plików na prywatne repo w git

    fs -> git

Server nodejs pokazujący pliki przez http
+ json
+ pdf
+ image
  update plików w bazie danych, w files



# Sql

## API

Localhost based on sqlite
get request

send pdf
send as base64
send as image

## Statements

duplicate columns
copy from Column one to another
replace value in duplciated column

update [table].[name]
set [columnname] =
(case when [columnname] like 'December 2017%'  then REPLACE([columnname], 'December 2017', '2018 December')
when [columnname] like ... then...
ELSE...
END)




## TODO [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/inframonit/docs/edit/CONTRIBUTION/TODO.md)


1. Dane: Helm, Gitlab Enterprises downgrade to community
2. Usługa: docker compose na device: NUC on ubuntu + kubernetes + camel
3. Przygotowanie usług lokalnie -> przez projekt gitlab uruchomienie  





# Tags

+ scripts
+ language

---

+ [readock-com/docs](https://github.com/readock-com/docs)
