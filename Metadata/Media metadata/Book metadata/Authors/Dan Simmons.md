---
Type: Author
---
```dataview
table Rating, Genre, Published-date
from "Media/Books"
Where contains(lower(Type), "book") and Author= [[Dan Simmons]]
sort Published-date asc
```
