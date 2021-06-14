---
layout: page
title: About
permalink: /about/
weight: 3
---

<style>
#attribution{
    visibility: hidden;
}    

.text-muted {
    visibility: hidden;
}
</style>

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
I am a graduate of Cal Poly SLO, with a BS in electrical engineering and a minor in computer science. I have taken a variety of technical classes covering advanced analog and digital circuit design, systems programming, and digital signal processing. My professional interests are in mixed signal analysis, system/device testing and fault analysis, and systems programming. Outside of
work, I am an avid reader, DIYer, and surfer.

{% include elements/button.html link="/images/Resume.pdf" text="Resume" block=true %}

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Software Skills" source=site.data.other-skills %}
</div>

<!-- <div class="row">
{% include about/timeline.html %}
</div> -->