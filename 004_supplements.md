---
layout: default
title: Supplements
number: 4
---

# Supplements

Do you have supplementary materials (such as media files) or links for further information for the reader? (minimum 3 additional media files or links)

# Timeline

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1DMujljENEv8umMK06V2RyqKhXUfWJCMRG-OqWwqucko&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe> 
# Supplementary Websites

Place your links here to websites that have information about your topic.

# Supplementary Media Files

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Capitalism-socialism'" %}
{% include media.html pages=media %}

