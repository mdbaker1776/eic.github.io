---
title: Software Working Group
name: swg
layout: default
---

{% include layouts/title.md %}

##### Conveners
{% include people/conveners.md %}
<br/>
Conveners' mailing list: <a href="mailto:eicug-software-conveners@eicug.org">eicug-software-conveners@eicug.org</a>
<hr/>

##### The Team

The Software Working Group includes more than 100 motivated physicists and software professionals with interest in
various aspects of EIC Software and Computing.
<br/>
The Software Group mailing list: <a href="mailto:eicug-software@eicug.org">eicug-software@eicug.org</a>
<hr/>

##### The Core Group
The core group consists of EICUG collaborators making frequent contributions to the effort.
{% assign people=site.data.people | sort: "name" %}

<table width="100%">
{% for who in people %}
<tr>
<td>{{ who.full }}</td>
<td><a href="mailto:{{ who.email }}">{{ who.email }}</a></td>
</tr>
{% endfor %}
</table>
<br/>
The Core Group mailing list: <a href="mailto:eicug-software-core@eicug.org">eicug-software-core@eicug.org</a>
<hr/>