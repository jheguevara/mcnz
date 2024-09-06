---
layout: minimal
title:  "More News"
blurb: "Here are the latest news articles and press releases."
date:   2022-01-01 01:11:00 -0500
categories: 
---

<h1>News</h1>
{% for post in site.posts %}			
<div style="border: 1px solid #DEDEDE;" class=" col-12 col-sm-12 col-md-12 col-lg-12 mb-1 mt-1">

               
               <div  style="border: 1px dashed #6831e3;" class="card mb-1 mt-2">
                  <div class="card-header">
                     <a href="/hide/{{ post.url }}">{{ post.title }}</a>
                  </div>
                  <div class="card-body">
                     <p class="card-text">{{ post.blurb }}</p>
                     <a href="/hide/{{ post.url }}" class="btn btn-primary btn-sm" >Learn more...</a>
                  </div>
               </div>
               



</div>
{% endfor %}