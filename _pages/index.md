---
layout: home 
permalink: /
author_profile: true
---

I'm an incoming Assistant Professor in the Computer Science Department at Johns
Hopkins University, starting Fall 2026. I'm looking for motivated students
interested in empirical research on network security and privacy. If that sounds
like you, please get in touch!

My work focuses on security and privacy vulnerabilities that affect real people
on the Internet. I collaborate with government and industry partners to
understand and address these problems. I enjoy exploring the systems we all rely
on&mdash;knowingly or not&mdash;and often assume to be secure or private.

Outside the lab, I’m an alliteration advocate, serial comma champion, diaeresis
disciple, ligature lover, and semicolon supporter. Kerning is pretty groovy. I’m
also an erratic (ultra)marathoner, erstwhile Marine, and devoted dog enthusiast.
My Erdős number is 3 (Gera → Chartrand → Erdős).

#### News

<ul class="news-list">
  {% for item in site.data.news %}
    <li><span class="news-date">{{ item.date }}</span> {{ item.title }}</li>
  {% endfor %}
</ul>

