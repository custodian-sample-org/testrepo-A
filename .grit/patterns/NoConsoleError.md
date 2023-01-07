---
title: Remove `console.error`
---
# {{ page.title }}

Remove `console.error` statements. 

tags: #good

```
`console.error($arg)` => . where {
  $arg <: not within CatchClause()
}
```
