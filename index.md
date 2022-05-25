---
title: Home
---

Soon... hopefully

{% for post in site.posts %}
<article class="project">
  <header>
    <h1 class="post-title">{{ page.title }}</h1>
    <p class="post-date"><small>{{ page.date | date_to_string }}</small></p>
  </header>
{{ content }}
</article>
{% endfor %}


<!--
# Hey!

I'm [Dimitri](/me), welcome on my website.

I mainly use this space to collect thoughts and ideas in the form of [notes](/notes).

You can see some [photoprojects](/projects) I'm working on.

This is what I'm doing [now](/now).

And there's also a list of the [books](/books) I read.

I wish you an excellent day!
-->
<!--
{% include image.html url="/assets/images/scottish.jpg" description="Scottish landscape" %}

{% include image.html url="/assets/images/geese.jpg" description="Geese flying out" %}
-->
