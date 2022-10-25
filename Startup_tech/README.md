# Struture de la DBB:

| Table 1 | users                        |
|-------------------|--------------------|
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| name | TEXT                            |

| article|
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| user_id | INTEGER |
| category_id | INTEGER |

| category |
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| title | TEXT |
| article_id | INTEGER |

| tag |
| id | INTEGER PRIMARY KEY AUTOINCREMENT |
| title | TEXT |
| color | TEXT |
| category_id | INTEGER |