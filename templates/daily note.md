---
creation-date: <% tp.file.creation_date() %> 
modification-date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %> 
---
pages: [[01 daily notes]] 
#daily-note
___

👈 [[<% tp.date.now("YYYY-MM-DD", -1) %>]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>]] 👉 

# <% tp.file.title %> 
<% tp.web.daily_quote() %>


## weather
<% tp.user.getWeather() %>

## what i want to do today: #todo
- [ ] meditate
- [ ] stretch 
- [ ] pt
- [ ] 50 pushups
- [ ] ab workout



## thoughts about the day / what i did:
- 

## energy check-in:
- physical::
- focus::
- emotional::

## random thoughts:
- 

## notes:
- 

## ![[Day Planner-<% tp.date.now("YYYYMMDD") %>|schedule]]