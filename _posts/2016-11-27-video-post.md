---
layout: post
title: "A Post with a Video"
description: "Custom written post descriptions are the way to go... if you're not lazy."
tags: [sample post, video]
categories: [intro]
---

{::nomarkdown}
<iframe width="560" height="315" src="https://www.youtube.com/embed/OXFCSBdJUx8" frameborder="0" allowfullscreen></iframe>
{:/nomarkdown}

Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).


<!-- more -->


Adding YouTube video embeds causes errors when building your Jekyll site. To fix wrap the html within `{::nomarkdown}` tags. Example below:

{% highlight html %}
{::nomarkdown}
<iframe width="560" height="315" src="//www.youtube.com/embed/SU3kYxJmWuQ" frameborder="0" allowfullscreen></iframe>
{:/nomarkdown}
{% endhighlight %}

## Demo asciinema-player

<asciinema-player src="/asciinema/fire.json" id="asciicast-14" ></asciinema-player>


## Fresponsive Iframe Cybermap


<figure class="half center">

<iframe src="https://cybermap.kaspersky.com/" frameborder="0" scrolling="no" width="336" height="566"></iframe>

</figure>


## tplmap

<style>
.responsive-wrap iframe{ max-width: 100%;}
</style>

<figure class="half center">
<div class="responsive-wrap">
<iframe src="https://github.com/epinna/tplmap/" frameborder="0" scrolling="auto" width="336" height="566"></iframe>
</div>
</figure>

