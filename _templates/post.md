---
title: <% tp.file.title %>
description: post <% tp.file.title %> description
date: <% tp.file.creation_date("YYYY-MM-DD") %>
modified: <% tp.file.last_modified_date("YYYY-MM-DD") %>
category: zettelkasten
layout: post
---

# <% tp.file.title %>


Reviewed by: 

<% await tp.file.rename(tp.file.creation_date("YYYY-MM-DD") + "-" + tp.file.title) %>