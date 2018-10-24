---
layout: default
title: Hutch GWC 
categories:
- home
---

<div class="row">
 <div class="col-md-12">
   <object class="pull-left biglogo" data="/images/gwc.png" type="image/svg+xml"></object>
   <div class="bigtitle logobox">
     Fred Hutch Girls Who Code club 2018-2019
   </div>
 </div>
</div>

<div class="bigspacer"></div>

<div class="row">
 <div class="col-md-12">
   <div class="smallhead">
     <p>
       The Fred Hutch Girls Who Code club is a group of high school girls and computational biology PhD
       students who come together once a week to work on fun and collaborative projects.
     </p>
     <p>
       We are loosely affliated with the national <a href="https://girlswhocode.com/">Girls Who Code</a> organization.
     </p>
   </div>
 </div>
</div>

<div class="bigspacer"></div>
<div class="bigspacer"></div>
<!--
<div class="row">
 <div class="col-md-12">
   <div class="head">
     <a class="off" href="/blog/">Recent posts</a>
   </div>
   <div class="spacer"></div>
 </div>
</div>

<div class="row">
 {% for post in site.categories.blog limit:4 %}

 {% for member in site.categories.team %}
   {% if member.title == post.author %}
     {% assign author = member %}
   {% endif %}
 {% endfor %}

 <div class="col-md-3 reduced-gutter">
   <div class="pad-left">
     <div class="note">
       <i class="fa fa-comment-o fa-fw"></i>
       <a class="off" href="{{ post.url }}">
       {{ post.title }}
       </a>
     </div>
     <div class="smallspacer"></div>
     <div class="smallnote">
       Posted
       {{ post.date | date: "%-d %b %Y" }}
       {% if post.author %}
       by <a class="off" href="
         {% for member in site.categories.team %}
           {% if member.title == post.author %}
             {{ member.url }}
           {% endif %}
         {% endfor %}
       ">
       {{ post.author }}
       </a>
       {% endif %}
       {% if post.authors %}
       by
       <a class="off" href="
         {% for member in site.categories.team %}
           {% if member.title == post.authors.first %}
             {{ member.url }}
           {% endif %}
         {% endfor %}
       ">
       {{ post.authors.first }}
       </a>
       and
       <a class="off" href="
         {% for member in site.categories.team %}
           {% if member.title == post.authors.last %}
             {{ member.url }}
           {% endif %}
         {% endfor %}
       ">
       {{ post.authors.last }}
       </a>
       {% endif %}
     </div>
     <div class="bigspacer"></div>
   </div>
 </div>
 {% endfor %}
</div>

<div class="spacer"></div>

<div class="row">
 <div class="col-md-12">
   <div class="head">
     <a class="off" href="/papers/">Recent papers</a>
   </div>
   <div class="spacer"></div>
 </div>
</div>

<div class="row">
 {% for paper in site.categories.papers limit:4 %}
 <div class="col-md-3 reduced-gutter">
   <div class="pad-left">
     <div class="note">
       <i class="fa fa-file-text-o fa-fw"></i>
       <a class="off" href="{{ paper.url }}">
       {{ paper.title }}
       </a>
     </div>
     <div class="smallspacer"></div>
     <div class="smallnote">
       Posted
       {{ paper.date | date: "%-d %b %Y" }}
     </div>
     <div class="bigspacer"></div>
   </div>
 </div>
 {% endfor %}
</div>

<div class="spacer"></div>

<div class="row">
 <div class="col-md-12">
   <div class="head">
     <a class="off" href="/projects/">Active projects</a>
   </div>
   <div class="spacer"></div>
 </div>
</div>

<div class="row">
 {% for project in site.data.projects limit:4 %}
 <div class="col-md-3 reduced-gutter">
   <div class="pad-left">
     <div class="note">
       <i class="fa fa-edit fa-fw"></i>
       <a class="off" href="{{ project.url }}">
       {{ project.title }} - {{ project.description }}
       </a>
     </div>
     <div class="smallspacer"></div>
     <div class="smallnote">
       Updated
       <a class="off" href="{{ project.commits.first.url }}">
       {{ project.commits.first.date | date: "%-d %b %Y" }}
       </a>
       by
       <a class="off" href="{{ project.commits.first.author_url }}">
       {{ project.commits.first.author_login }}
       </a>
     </div>
     <div class="bigspacer"></div>
   </div>
 </div>
 {% endfor %}
</div>

<div class="spacer"></div>

<div class="row">
 <div class="col-md-12">
   <div class="head">
     Misc
   </div>
   <div class="spacer"></div>
 </div>
</div>

<div class="row">
 <div class="col-md-12 reduced-gutter">
   <div class="pad-left">
     <ul class="list-inline">
       {% for page in site.categories.misc %}
       <li class="footernav">
         <i class="fa fa-angle-right"></i> <a class="off" href="{{ page.url }}">{{ page.title }}</a>
       </li>
       {% endfor %}
       <li class="footernav">
         <i class="fa fa-angle-right"></i> <a class="off" href="/talks/">Talks</a>
       </li>
       <li class="footernav">
         <i class="fa fa-angle-right"></i> <a class="off" href="http://www.fredhutch.org/">Fred Hutch</a>
       </li>
     </ul>
   </div>
   <div class="spacer"></div>
 </div>
</div> -->
