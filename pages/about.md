---
layout: page
title: About
description: 程序简化信息交流
keywords: xujiantao, University of Aizu
menu: 关于
permalink: /about/
---

My name is Xu Jiantao.

Studing at Aizu University in Japan.

Believe that practice makes perfect, and strive to change your life.

## Contact Me

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
<li>E-mail:  xujiantao9510@gmail.com</li>
<li>wechat:  a963345284</li>
<li>Phone:   86-176-3390-8831</li>
<li>QQ:      963345284</li>
<li>
WeChat：<br/>
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="xujiantao9510/xujiantao9510.github.io/assets/images/qrcode.jpg" alt="a963345284" />
</li>
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
