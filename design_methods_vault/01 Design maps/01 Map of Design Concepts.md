
## All design concepts and principles
```dataview
LIST 
FROM "02 Concepts" OR #concepts 
```


## All design concepts grouped per tags 
```dataview
TABLE without id tags,rows.file.link
FROM "02 Concepts"
FLATTEN tags
GROUP BY tags
```
