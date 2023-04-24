---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hello, I am **{{ site.author.name }}** :wave:.<br>
I a programmer (an eternal computer student). I am trying to be an amateur cellist and animal lover.

[Here is my curriculum Lattes](http://lattes.cnpq.br/9266478603595600)


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
