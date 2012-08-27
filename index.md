---
layout: page
title: nick32m.github.com | Nick Luo Homepage
tagline: nick.luo@me.com
theme :
  name : twitter
description: Nick Luo's Home Page
keywords: nick luo, liwei luo, nick luo's homepage, liwei luo's homepage, nick luo github, nick luo github page, passionate software developer, passionate software engineer, python/django developer, iOS developer, iphone developer , web application developer

---
{% include JB/setup %}

<div class ="marketing">
  <div class="row">
    <div class = "span2">
      <!-- put my image here --> 
      <img class ="img-rounded" src="{{ ASSET_PATH }}/photos/nick.jpg" alt="Nick Luo">  
<!--       <ul class="socialicons">
        <li> <a href=""> i </a> </li>
      </ul> -->
    </div>


    <div class="span7">
      <!-- <div class="hero-unit" style="padding:20px"> -->
<!--         <div class= "page-header">
          <h2>
            {{ page.title }} 
            {% if page.tagline %} 
              <small>{{ page.tagline }}</small>
            {% endif %}
          </h2>
        </div> -->
        <p class="description"> 
          Hi I am Nick Luo. I am a passionate software developer. I love making software. 
          <br/>In my spare time, I like to learn new technologies participate programming contests in interviewstreeet.com. I love eating sushi too. You could find out more about me at: 
        </p>
        <br/>
        <div class= "row-fluid">
          <div class="span3">
            <button class="btn btn-primary btn-large "><b> More about Me </b></button> 
          </div>
          <div class="span6 offset2">
            <ul class="socialicons">
              <li> <a data-icon="!" href=""> </a> </li>
              <li> <a data-icon='$' href="https://github.com/nick32m/"> </a> </li>
              <li> <a data-icon="&#x22;" href="">  </a> </li>
              <li> <a data-icon="&#x26;" href="">  </a> </li>
            </ul>
          </div>
        </div>        
     <!-- </div> -->
    </div>
  </div>
</div>

   <!--      <a href="https://github.com/nick32m/"><img alt="Nick Luo  @ Github" src="{{ ASSET_PATH }}/images/github.png" /></a>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  
      
        <a href="https://github.com/nick32m/"><img alt="Nick Luo  @ Google+" src="{{ ASSET_PATH }}/images/google-plus.png" /></a>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

         <a href="http://au.linkedin.com/pub/nick-luo/38/829/748">
          <img src="http://www.linkedin.com/img/webpromo/btn_myprofile_160x33.png" width="160" height="33" border="0" alt="View Nick Luo's profile on LinkedIn">
        </a> &nbsp;&nbsp;  &nbsp;&nbsp;  &nbsp;&nbsp;     

        <a href="https://twitter.com/nick32m" class="twitter-follow-button" data-show-count="false" data-size="large">Follow @nick32m 
        </a>
         -->
        
 
 <div class="row">
  <div class="span9 offset2">
    <h3> <!--&raquo; --> Recent Blog Posts </h3>
    <ul class ="posts">
      {% for post in site.posts limit:5 %}
          <li style="line-height: 12px">
            <h5><span>{{ post.date | date_to_string }}</span></h5> <!-- &raquo; --> 
            <p>&raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></p>

          </li>
      {% endfor %}
    </ul>
  </div>
 </div>
<!-- Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples. -->


