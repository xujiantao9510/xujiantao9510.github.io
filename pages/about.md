---
layout: page
title: About
description: 关于我的界面
keywords: xujiantao, University of Aizu
menu: 关于
permalink: /about/
---

My name is Xu Jiantao.

Studing at Aizu University in Japan.

Believe that practice makes perfect, and strive to change your life.

## Contact Me

<ul>
<li>E-mail:&nbsp;&nbsp;&nbsp;&nbsp;xujiantao9510@gmail.com</li>
<li>WeChat:&nbsp;a963345284</li>
<li>Tel:&nbsp;&nbsp;&nbsp;86-176-3390-8831</li>
<li>QQ:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;963345284</li>
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
