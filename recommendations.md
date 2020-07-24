---
title: Recommended Reads
permalink: /recommend/
layout: page

---
 <blockquote class="embedly-card"><h4><a href="https://ridhirebuts.github.io/WhyIStoppedWatchingTheDailyShow/">Why I Stopped Watching The Daily Show with Trevor Noah</a></h4><p>I'll start out with this: My whole life, I was surrounded by a lot of Western influences. I watched Disney Channel, American sitcoms, I read (and actually still read) the BBC and New York Times religiously (although I don't always agree with what they say) and the Western media has played a very large role in shaping how I approach things.</p></blockquote>
 
 <blockquote class="embedly-card"><h4><a href="https://www.bariweiss.com/resignation-letter">Resignation Letter - Bari Weiss</a></h4><p>Dear A.G., It is with sadness that I write to tell you that I am resigning from The New York Times. I joined the paper with gratitude and optimism three years ago. I was hired with the goal of bringing in voices that would not otherwise appear in your pages: first-time writers, centrists, conservatives and others who would not naturally think of The Times as their home.</p></blockquote>




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
