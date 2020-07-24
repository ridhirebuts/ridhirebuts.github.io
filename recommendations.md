---
title: Recommended Reads
permalink: /recommend/
layout: default

---

<div class="posts">
  {% for linker in site.linker %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="date">
    {{ post.date | date: "%B %e, %Y" }}
      </div>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>




















<!-- <div>
    {% assign categories = site.categories | sort %}
    {% for category in categories %}
<!--         <span class="site-tag">
            <a href="#{{ category | first | slugify }}">
                    {{ category[0] | replace:'-', ' ' }} ({{ category | last | size }})
            </a>
        </span> -->
    {% endfor %}
</div>
<div id="index">
   
    {% for category in categories %}
<!--         <a name="{{ category[0] }}"></a>
        <h2>{{ category[0] | replace:'-', ' ' }} ({{ category | last | size }})</h2> -->
        {% assign sorted_posts = site.posts | sort: 'title' %}
        {% for post in sorted_posts %}
            {%if post.categories contains category[0]%}
    
      <article class="post">

      <h1><a href="{{{ site.url }}{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="date">
    {{ post.date | date: "%B %e, %Y" }}
      </div>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
             
                
         
            {%endif%}
        {% endfor %}
    {% endfor %}
</div> -->
