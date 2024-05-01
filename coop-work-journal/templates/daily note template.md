---
Creation Date: <% tp.file.creation_date() %>
Modification Date: <% tp.file.last_modified_date("MMMM Do YYYY HH:mm:ss") %>
---

<- [[<% tp.date.now("YYYY-MM-DD", -1) %>]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>]]  ->

# <% tp.file.title %>