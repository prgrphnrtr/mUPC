---
fileClass: term
aliases: Berichterstatter
---

## General

### Related Rules

- [[UPCRoP#Rule 18 - Designation of the judge-rapporteur]]

## Notes

````dataview 
list where contains(this.file.inlinks, file.link) and !contains(this.file.outlinks, file.link)
sort file.ctime asc
````
