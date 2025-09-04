---
title: Online gehostete Anweisungen
permalink: index.html
layout: home
---

Die Hyperlinks zu den einzelnen Demos sind unten aufgeführt.

## Demos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Beispiel-Eingabeaufforderungen für eine interaktive Erfahrung

#### [Führungskräfte](https://learn.microsoft.com/en-us/training/modules/envision-new-ideas-with-microsoft-365-copilot/) (Leitet zu Microsoft Learn um)

#### [Kommunikation](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Communications-Prompts.html)

#### [Personalverwaltung](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/HR-Prompts.html)

#### [Vertrieb](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Sales-Prompts.html)

#### [IT](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/IT-Prompts.html)

#### [Geschäftsleitungsassistenz](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EA-Prompts.html)

#### [Business Manager](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Business-Manager-Prompts.html)

#### [Marketing](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Marketing-Prompts.html)

#### [Operations](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Operations-Prompts.html)

#### [Rechtliche Hinweise](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Legal-Prompts.html)

#### [Finance](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Finance-Prompts.html)

#### [Agents – geschäftliche Benutzende](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EU-Agents.html)

#### [Agents – Führungskräfte](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Exec-Agents.html)