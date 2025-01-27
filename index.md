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

## Sample Prompts for immersion experience

### [Executives](https://learn.microsoft.com/en-us/training/modules/envision-new-ideas-with-microsoft-365-copilot/) (MS Learn)

### [Communications](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Communications-Prompts.html)

### [HR](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/HR-Prompts.html)

### [Sales](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Sales-Prompts.html)

### [IT](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/IT-Prompts.html)

### [Executive Assistant](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EA-Prompts.html)

### [Business Manager](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Business-Manager-Prompts.html)