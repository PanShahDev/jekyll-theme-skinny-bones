---
layout: home
permalink: /
title: "Welcome"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
   <div class="page-lead" style="background-image:url(https://mmistakes.github.io/jekyll-theme-skinny-bones/images/wood-texture-1600x800.jpg)">
      <div class="wrap page-lead-content">
        <h1>Skinny Bones</h1>
        <h2>Jump start your Jekyll site with something thin and light.</h2>
        <a href="https://mmistakes.github.io/jekyll-theme-skinny-bones/getting-started/" class="btn-inverse">Start Using Skinny Bones</a> &nbsp; or &nbsp; <a href="https://github.com/mmistakes/jekyll-theme-skinny-bones" class="btn-inverse">View on GitHub</a>
      </div><!-- /.page-lead-content -->
    </div><!-- /.page-lead -->
{% endfor %}
</div>
<!-- /.tiles -->

<div id="js-menu-screen" class="menu-screen"></div>


    
  
    




<div class="tile">
  <h2 class="post-title">Built for Jekyll 3</h2>
  <p class="post-excerpt">Takes advantage of native Sass support and data files to make customizing your site easier.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Content First</h2>
  <p class="post-excerpt">Designed to put the focus on you and your writing. Headers, navigation, sidebars, and footers have been purposely deemphasized.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Customizable</h2>
  <p class="post-excerpt">Packed with layouts and modules. Include Disqus comments, social sharing buttons, and table of contents on one or all pages.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Extensible</h2>
  <p class="post-excerpt">Compatible with popular libraries like <a href="http://bourbon.io">Bourbon</a>, <a href="http://neat.bourbon.io/">Neat</a>, and <a href="http://github.com/octopress/octopress">Octopress</a> to help build and deploy your site with ease.</p>
</div><!-- /.tile -->

</div>
<!-- /.tiles -->
