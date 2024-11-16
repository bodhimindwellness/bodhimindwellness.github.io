---
layout: default
---
![Retreats 2025](/assets/images/retreatssmallgif.gif)
<div class="home">
  
  <h1 class="page-heading">Upcoming Retreats</h1>

   <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <!--<span class="post-meta">published on  {{ post.date | date: "%b %-d, %Y" }}-->
        <!--This is a comment. Comments are not displayed in the browser-->

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
 <iframe width="560" height="315" src="https://www.youtube.com/embed/0jZRRNORfBg?autoplay=1&mute=1&loop=1&playlist=0jZRRNORfBg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
 

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

 

</div>