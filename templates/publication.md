---
publication: true
category: 
icon: LiNewspaper
homepage: 
tags:
  - library
  - publication
---

> [!todo] Labels
> - [ ] for `category`, enter whether this is a journal, magazine, or newsletter
> - [ ] add the appropriate tag
> - [ ] add the library name tag and update queries with this as well
> - [ ] remove this callout

# articles
```dataview
LIST
FROM
	#library AND
	!#author
WHERE
	contains(publications, [[{{title}}]])
```

# contributors
```dataview
LIST
FROM
	#library AND
	#author
WHERE
	contains(publications, [[{{title}}]])
```
