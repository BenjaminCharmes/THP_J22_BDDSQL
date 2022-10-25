# Struture de la DBB:

| Table 1 | users                        |
|-------------------|--------------------|
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| name | TEXT                            |

| Table 2 | article |
| --- | --- |
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| user_id | INTEGER |
| category_id | INTEGER |

| Table 3 | category |
| --- | --- |
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| title | TEXT |
| article_id | INTEGER |

| Table 4 | tag |
| --- | --- |
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| title | TEXT |
| color | TEXT |
| category_id | INTEGER |