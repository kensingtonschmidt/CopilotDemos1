---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

Hyperlinks to each of the demos are listed below.

## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

---
title: Immersion Experience
layout: default
---

## Sample Prompts for Immersion Experience



## Sample Prompts for immersion experience


#### [Legal](https://emontes07.github.io/Learning/Instructions/Prompts/Legal-Prompts.html)

#### [Finance](https://emontes07.github.io/Learning/Instructions/Prompts/Finance-Prompts.html)

#### [Agents - Business Users](https://emontes07.github.io/Learning/Instructions/Prompts/EU-Agents.html)

#### [Agents - Executives](https://emontes07.github.io/Learning/Instructions/Prompts/Exec-Agents.html)
