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

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>