```dataview 
LIST file.ctime
```


```dataview 
LIST FROM "1️⃣ Primary Sources" where rating = "5/5"
```

```dataview
LIST
FROM "📆 Activity"
```
```dataview
LIST
WHERE file.mtime >= date(today) - dur(1 week)
```
```dataview
TABLE workout
FROM "2️⃣ Collections"
SORT file.ctime DESC
LIMIT 14
```

```dataview
TASK
WHERE !completed
LIMIT 10
GROUP BY file.link
SORT rows.file.ctime ASC
```
```dataview
CALENDAR file.mtime
FROM ""
```

```dataview
TASK
```