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

