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
 <iframe width="560" height="315" src="https://www.youtube.com/embed/Xi3w_0UFU0Y?si=tsSZCjlgtNO20O5l" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
 

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

 

</div>