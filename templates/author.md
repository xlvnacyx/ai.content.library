---
author: true
icon: LiUserPen
category: author
homepage: 
publications: 
keywords: 
tags:
  - library
  - author
---

> [!todo]
> - [ ] add tag for library name
> - [ ] include library name tag in publication dataview queries and included query
> - [ ] remove this callout

# articles
```dataview
LIST
FROM
	#library AND
	"#library name tag"
WHERE
	contains(authors, [[{{title}}]])
```

