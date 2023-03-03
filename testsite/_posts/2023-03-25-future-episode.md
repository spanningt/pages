---
layout: default
title:  "Future Episode"
videoid: 
channel: aws
date:   2023-03-25 10:30:00 -0800
---
{{ page.date | date: "%-d %B %Y" }}

<h1> {{ page.title}} </h1>

Future Episode


<div class="video-container">
    <iframe src="https://player.twitch.tv/?video={{ page.videoid | default: page.channel }}&parent=pages.tomadamski.net&parent=127.0.0.1&autoplay=false" height="315" width="560" allowfullscreen="" frameborder="0">
    </iframe>
</div>
