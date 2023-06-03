Project Tag: #projects/{{title}}

# Project Details

# Links

# Notes tagging this project
```dataviewjs
const title = dv.current().file.name

dv.list(
  dv.pages("#projects/"+title).file.link
)
```