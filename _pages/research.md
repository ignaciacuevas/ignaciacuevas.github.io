---
layout: archive
title: "Research & Work in Progress"
permalink: /research/
author_profile: true
---

## **Supply Chain Disruptions and Diversification (JMP)**, joint with Thomas Bourany and Gustavo González. R&R JIE. [[Link](https://www.bcentral.cl/documents/33528/133326/DTBC_1018.pdf/cb2b41e8-59a0-00dc-d346-ecb66ddbb549?t=1718289102492)]

<span style="font-size:0.9em;line-height:-1em;"> **Abstract**: How do firms adapt their sourcing strategies when faced with supply chain uncertainty? To answer this question, we develop a multi-country sourcing model, in which firms choose where to import from, accounting for the possibility of supply-chain disruptions. We show that uncertainty introduces a positive option value, that favors diversifying the set of suppliers. However, country-specific uncertainty creates hedging motives for firms, yielding on net ambiguous predictions about sourcing decisions. We estimate the model on Chilean Customs data and we study how the recent increase in trade risk, following the Covid-19 pandemic, affected firms’ sourcing strategies. We find that the observed change in sourcing patterns results from both changes in expected costs and increased risk.
</span>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
