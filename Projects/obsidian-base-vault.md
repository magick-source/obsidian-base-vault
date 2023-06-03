Project Tag: #projects/obsidian-base-vault

# Project Details

The goal of the **Obsidian Base Vault** project is to create a base vault, that I can copy when I want to create a new vault.

I usually create a new vault when I start on a new client or job to allow me to keep all the information about the projects of that job or client contained - this way when I move to a different job or client I can simply delete or archive that vault and not risk having confidential details of a client shared with a different client.

This project makes it easier for me to set up a new vault, as it already have all the plugins configured as I like them and have the right note structure.

# Links

- Github repo: https://github.com/magick-source/obsidian-base-vault

# Notes tagging this project
```dataviewjs
const title = dv.current().file.name

dv.list(
  dv.pages("#projects/"+title).file.link
)
```