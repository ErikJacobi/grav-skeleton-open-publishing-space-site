---
title: Blog
media_order: Bomenbladerdek.png
published: false
hide_git_sync_repo_link: true
body_classes: 'header-dark header-transparent'
hero_classes: 'text-light title-h1h2 overlay-dark-gradient hero-large parallax'
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
content:
    items:
        - '@self.children'
    limit: 6
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
bricklayer_layout: true
display_post_summary:
    enabled: false
feed:
    limit: 10
    description: 'Sample Blog Description'
sitemap:
    changefreq: monthly
modular_content:
    items: '@self.modular'
    order:
        by: folder
        dir: dsc
pagination: true
---

# Welkom bij de **koele boom**
## Geniet, lees en deel je ervaring
