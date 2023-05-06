---
Type: Author
---
```dataview
table Rating, Genre, Published-date
from "Media/Books"
Where contains(lower(Type), "book") and Author= [[Andy Weir]]
sort Published-date asc
```
