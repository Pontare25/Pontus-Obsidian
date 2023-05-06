---
Type: Author
---
---
Type: Author
---
```dataview
table Rating, Genre, Published-date
from "Media/Books"
Where contains(lower(Type), "book") and Author= [[James Clear]]
sort Published-date asc
```
