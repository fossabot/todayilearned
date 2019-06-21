---
title: Create + reference a native CSS variable
tags:  ["CSS3"]
goal:  Front-End Engineering
date:  2019-06-08

---

```css
:root {
  --scale: scale(1.1);
  --primary-color: #00FF00; 
}
```
…
```css
.btn { transform: var(--scale); }
.foo { color: var(--primary-color); }
/* etc */
```

{{< codepen id="vwZWPz" tab="css" >}}

