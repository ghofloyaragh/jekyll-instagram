---
layout: company
name: KALE KILIT 
website: https://www.kalekilit.com
nationality: Turkey
---
{% assign data = site.data.kale%}

{% assign data = site.cards|where:"company" , page.name%}
{% include 3x3grid.html%}