---
publication: true
category: newsletter
icon: LiNewspaper
homepage: https://www.sustainabilitybynumbers.com
tags:
  - library
  - publication
  - newsletter
  - ai
---

# articles
```dataview
LIST
FROM
	#library AND
	#ai AND
	!#author
WHERE
	contains(publications, [[Sustainability by Numbers]])
```

# contributors
```dataview
LIST
FROM
	#library AND
	#ai AND
	#author
WHERE
	contains(publications, [[Sustainability by Numbers]])
```
