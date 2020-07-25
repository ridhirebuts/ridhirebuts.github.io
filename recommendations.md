---
title: Recommended Reads
permalink: /recommend/
layout: default

---
<blockquote class="embedly-card"><h4><a href="https://ridhirebuts.github.io/Religious-persecution-in-pakistan/">Religious Persecution in Pakistan</a></h4><p>In his first speech before the members of the Constituent Assembly of Pakistan in 1947, Mohammad Ali Jinnah said that non-Muslims would be equal citizens in the new country and that every person living in the country would be an equal citizen, irrespective of his or her community, caste, colour, or faith.</p></blockquote>
<script async src="//cdn.embedly.com/widgets/platform.js" charset="UTF-8"></script>



<blockquote class="embedly-card"><h4><a href="https://blog.usejournal.com/the-pulitzer-is-a-portal-b157bc0f6850">The Pulitzer is a Portal</a></h4><p>In particular, one photograph from the set (see left, above)- that of a "masked Kashmiri protester jump[ing] on the bonnet" of a J&K police vehicle provides an interesting parallel to at least two other Pulitzer Prize-winning photographs from previous years.</p></blockquote>
<script async src="//cdn.embedly.com/widgets/platform.js" charset="UTF-8"></script>








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
