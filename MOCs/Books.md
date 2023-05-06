```dataview
table without ID rows.file.link as Title, rows.Genre as Genre,  rows.Author as Author, rows.Rating as Rating
from "Books"
where contains(lower(Type), "book")
Flatten Genre
group by Genre
```
