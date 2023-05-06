
```dataview
table Genre,  Author, Rating, Published-date as Date
from "Media/Books"
where contains(lower(Type), "book")
```
