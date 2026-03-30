---
layout: page
title: submenus
# Set nav: true when Bookshelf / Blog are ready to show in the navbar again.
nav: false
nav_order: 8
dropdown: true
children:
  - title: bookshelf
    permalink: /books/
  - title: divider
  - title: blog
    permalink: /blog/
---

This dropdown is **under construction**. **Bookshelf** and **Blog** are hidden from the navigation bar until you set `nav: true` above.

{% comment %}
The navbar only lists pages with nav: true. Submenu entries stay in `children` for when you re-enable the dropdown.
{% endcomment %}

