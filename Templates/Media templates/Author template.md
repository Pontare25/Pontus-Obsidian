---
Type: Author
Cover:
---
`="![AuthorCover|250](" + this.cover + ")"`
[[Authors]]
```dataview
table Rating, Genre, Published-date
from "Media/Books"
Where contains(lower(Type), "book") and Author= [[<% tp.file.title %>]]
sort Published-date asc
```
