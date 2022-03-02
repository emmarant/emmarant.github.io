---
permalink: /publications/
title: ""
excerpt: "publications"
author_profile: true
---


{% include base_path %}

{% for post in site.publications reversed %}
**{{post.title}}**
<br>
{{post.citation}}
<br>
<a href="{{post.paperurl}}"><i class="fas fa-fw fa-link" aria-hidden="true"></i></a>



{% endfor %}


 



