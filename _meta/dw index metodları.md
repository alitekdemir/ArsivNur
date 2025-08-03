```dataview1
TABLE
  konu AS Konu
FROM "01 Afyon"
SORT no ASC
```


```dataview1
TABLE WITHOUT ID
    link(file.path, id) AS "Mektup",
    konu AS Konu,
    tarih AS Tarih
FROM "01 Afyon"
SORT no ASC
```


```dataview1
LIST konu
FROM "01 Afyon"
SORT no ASC
```

```dataview1
TABLE WITHOUT ID
  link(file.path, konu) AS ""
FROM "01 Afyon"
SORT no ASC
```


```dataview1
TABLE WITHOUT ID
  link(file.path, no + ": " + konu) AS ""
FROM "01 Afyon"
SORT no ASC
```

