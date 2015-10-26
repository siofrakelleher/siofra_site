---
title: Latest Posts

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 100
    pagination: true

feed:
    description: Sample Blog Description
    limit: 8

pagination: true
---

