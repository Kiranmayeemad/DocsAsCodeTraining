---
first: Kiranmayee
layout: TemplateDemo 
---

# Homepage 

My name is {{ page.first }}

I have a class at {{ site.When }}

{% item in site.data.employment %}
{{ item.company }}, {{ item.years }}
{% endfor %}

1. Pls go to Settings.
2. Scroll down and go to **GitHub Pages**.
3. Click on **None**.
4. Select Main, Select root and click on Save
5. Wait for few seconds.
6. You can see the URL where the code is published as Website.
7. Click on the URL, you can see the **Readme** file in the browser.
