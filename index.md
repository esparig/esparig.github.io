---
layout: home
---
<article class="post">

  <header class="post-header">
    <h1 class="post-title">{{ page.title | escape }}</h1>
  </header>

  <div class="center">
    <a href="{{ site.base_url }}">
      {% include image.html path=site.thumbnail_path alt=site.name %}
      </a>
  </div>

  <div class="post-content">
    <div class="col sm-col-9 px2">
      <h2 class="footer-heading">About me</h2>
      <p>{{- site.description | escape -}}</p>
    </div>
    <div class="col sm-col-3 px2">
      <h2 class="mb2">Contact</h2>
      {% include contact.html %}
  </div>  
  </div>

</article>
