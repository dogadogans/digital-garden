---
tags: ⚙️
aliases: 
cssclass:
---

%% This note requires the data view plugin %%

```dataview
list 
from "" AND !"Journal" AND !"Templates"
where file.day = null AND type != null
sort file.day desc
```

---

```dataview
list
from "" AND !"Journal"
where type != null AND file.day
sort file.day desc
```


