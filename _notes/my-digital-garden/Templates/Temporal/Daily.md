---
tags:
publish: false
aliases: 
---

## On This Day...

[[<%tp.date.now("YYYY-MM-DD", -365)%>]]

---

## Notes Created Today

---

[[<% tp.date.yesterday("YYYY-MM-DD") %>]] <== <button class="date_button_today">Today</button> ==> [[<% tp.date.tomorrow("YYYY-MM-DD") %>]]

#### Whats On Your Mind? 

##### Goals

TBD

---

<%* if (tp.date.now("M-D") == "1-1") { %>
- [ ] Make Yearly Note
<%* } _%>
<%* if (tp.date.now("D") == 1) { %>
- [ ] Make Monthly Note
<%* } _%>
<%* if (tp.date.now("ddd") == "Sun") { %>
- [ ] Make Weekly Note
<%* } _%>
<% tp.file.cursor(7) %>