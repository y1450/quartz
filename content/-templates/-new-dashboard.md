---
title: 📰 New Dashboard
type: dashboard
description: A basic structure file that can be used to create dashboards
---
%%
Status:: #triage 
%%

---
**Tags**:: #dashboard
**Links**::

---

## Dashboard Info

You can [🎯 Create Custom Dashboards] easily using the `dataview` plugin and SQL-like query language.

---

## All Current Dashboards
```dataview
table description as "Description" 
where type = "dashboard"
sort file.name ASC
```