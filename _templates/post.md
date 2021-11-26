---
title: <% tp.file.title %>
description: post <% tp.file.title %> description
date: <% tp.file.creation_date("YYYY-MM-DD") %>
modified: <% tp.file.last_modified_date("YYYY-MM-DD") %>
category: code
layout: default
---

# <% tp.file.title %>

<% await tp.file.rename(tp.file.creation_date("YYYY-MM-DD") + "-" + tp.file.title) %>