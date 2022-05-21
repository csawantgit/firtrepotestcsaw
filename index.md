---
year: 1883
layout: demo_template
---
{% include footer.txt %}

# firtrepotestcsaw

It all started in the year {{page.year}} by {{site.author}}.

{% for item in site.data.chronology %}
- {{ item.name }}, {{ item.place }}
{% endfor %}

# Markdown Test Content

This is my first markdown **overview** line.
## This is an unordered list

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.

## This is an ordered list

1. [AngularJS] - HTML enhanced for web apps!
1. [Ace Editor] - awesome web-based text editor
1. [markdown-it] - Markdown parser done right. Fast and easy to extend


And, this is a link to [www.google.com](google).

| Year | Place |
| ----- | ----- |
| 1825 | New Brunswick |
| 1845 | Oregon |
| 1870 | Quebec |
| 1871 | Wisconsin |

{% if Profile.PREFERED_LANGUAGE == "Spanish" %} 
Hola!
{% elsif Profile.PREFERED_LANGUAGE == "English" %}
Hello! 
This is a conditonal tag example.
{% else %}
Hello!
{% endif %}


{% assign eyes = "stars" %}
The {{ eyes }} sparkled and twinkled like bejewelled
sword handles.

This is a variable test.


| Years | Company |
| ... | ... |
| 1972 | It happened |
| 1999 | Did it happen |

```
imports requests
printf ("This is a code block")
```

Issue the following command : `git clone...`

![test image](https://www.pexels.com/photo/green-and-blue-peacock-feather-674010/)
