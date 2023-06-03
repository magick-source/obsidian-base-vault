Goal Tag: #goals/{{title}}

## Milestones


## Notes referencing this Goal
```dataviewjs
const title = dv.current().file.name

dv.list(
  dv.pages("#goals/"+title).file.link
)
```
