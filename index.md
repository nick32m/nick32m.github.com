---
layout: page
title: Nick Luo
tagline: nick.luo@me.com
theme :
  name : twitter
description: Nick Luo's Home Page
keywords: nick luo, liwei luo, nick luo's homepage, liwei luo's homepage, nick luo github, nick luo github page, passionate software developer, passionate software engineer, python/django developer, iOS developer, iphone developer , web application developer

---
{% include JB/setup %}

<div class="hero-unit">
  <div class="row">
    <div class = "span2">
      <img class ="img-circle" src="{{ ASSET_PATH }}/photos/nick.jpg" alt="Nick Luo" width="140px" height="140px">
    </div>
    <div class="span8" style="float:right">
      <h2> About me </h2>
          <p> 
            Hi I am Nick Luo, I am a passionate software engineer/developer currently residing in Brisbane, Australia. In my current work, I am specialised in developing secure web applications ,iPhone/iPad applications development. I also have great interests on the following areas:
          </p>
          <ul>
            <li> <p> Algorithms designed and implementation </p> </li>
            <li> <p>Scaling web applications (Although I don't have experience on it,yet) </p></li>
            <li> <p> Solve challenging problems</p> </li>
          </ul>

          <p> 
            I am also a great fan of Apple. I use iMac at work and Macbook Pro at home. I use sublime text on programming. I have a great exposure to Apple's Cocoa Framework and really like the design patterns and the extra (NS) libraries it has added to Objective-C language , makes a very enjoyable experience to program on iOS/OSX platform.
          </p>

          <p> 
            I am also a big fan of open source software. In my own time, I love exposuring Github and see what has been happening in the open source community.
          </p>
    </div>
  </div>

</div>


<div class ="marketing">
  <div class="row">
    <div class = "span3">
      <!-- put my image here -->
      <img class ="img-rounded" src="{{ ASSET_PATH }}/photos/nick.jpg" alt="Nick Luo">

<!--       <ul class="socialicons">
        <li> <a href=""> i </a> </li>
      </ul> -->
    </div>


    <div class="span9">
      <!-- <div class="hero-unit" style="padding:20px"> -->
<!--         <div class= "page-header">
          <h2>
            {{ page.title }} 
            {% if page.tagline %} 
              <small>{{ page.tagline }}</small>
            {% endif %}
          </h2>
        </div> -->
        <h2> About me </h2>
        <p> 
          Hi I am Nick Luo, I am a passionate software engineer/developer currently residing in Brisbane, Australia. In my current work, I am specialised in developing secure web applications ,iPhone/iPad applications development. I also have great interests on the following areas:
        </p>
        <ul>
          <li> <p> Algorithms designed and implementation </p> </li>
          <li> <p>Scaling web applications (Although I don't have experience on it,yet) </p></li>
          <li> <p> Solve challenging problems</p> </li>
        </ul>

        <p> 
          I am also a great fan of Apple. I use iMac at work and Macbook Pro at home. I use sublime text on programming. I have a great exposure to Apple's Cocoa Framework and really like the design patterns and the extra (NS) libraries it has added to Objective-C language , makes a very enjoyable experience to program on iOS/OSX platform.
        </p>

        <p> 
          I am also a big fan of open source software. In my own time, I love exposuring Github and see what has been happening in the open source community.
        </p>
        <br/>

        <div class="row">
          <div class="span1">
             <a href="https://github.com/nick32m/"><img alt="Nick Luo @ Github" src="{{ ASSET_PATH }}/images/github.png" /></a>
          </div>

          <div class="span2">
             <a href="http://au.linkedin.com/pub/nick-luo/38/829/748">
                <img src="http://www.linkedin.com/img/webpromo/btn_myprofile_160x33.png" width="160" height="33" border="0" alt="View Nick Luo's profile on LinkedIn">
            </a>
          </div>

          <div class="span2" style="margin-left:20px">
             <a href="https://twitter.com/nick32m" class="twitter-follow-button" data-show-count="false" data-size="large">Follow @nick32m 
            </a>
          </div>
           <div class="span1" style="margin-left:0px">
             <!-- <a href="https://github.com/nick32m/"><img alt="Nick Luo  @ Google+" src="{{ ASSET_PATH }}/images/google-plus.png" /></a> -->

             <!-- Place this code where you want the badge to render. -->
            <a href="//plus.google.com/109304259444226563362?prsrc=3" rel="publisher" style="text-decoration:none;">
            <img src="//ssl.gstatic.com/images/icons/gplus-32.png" alt="Nick Luo's Google+" style="border:0;width:32px;height:32px;"/></a>
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


