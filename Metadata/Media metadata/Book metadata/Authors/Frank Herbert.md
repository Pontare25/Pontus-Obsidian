---
Type: Author
---
```dataview
table Rating, Genre, Published-date
from "Media/Books"
Where contains(lower(Type), "book") and Author= [[Frank Herbert]]
sort Published-date asc
```
