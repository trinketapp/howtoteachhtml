---
layout: default
title: Welcome!
description: This is my site. Welcome.
keywords: github pages, Jekyll, foundation 5
id: index
---
<div class="bluebg fullheight">
  <div class="row text-center">
    <div class="small-10 columns small-centered">
      <div class="row">
        <div class="panel clearbg"><h1 id="bigtitle">Learn, Teach, And Share HTML</h1></div>
      </div>
    </div>
  </div>
  <!--Welcome Video-->
  <div class="row">
    <div class="small-12 columns small-centered" style="max-width: 800px">

<!--         <div class="small-10 columns small-centered" style="max-width: 800px;"> -->
<div id="wistia_opckf0l87m" class="wistia_embed" style="width:800px;height:500px;">&nbsp;</div>
<script charset="ISO-8859-1" src="//fast.wistia.com/assets/external/E-v1.js"></script>
<script>
wistiaEmbed = Wistia.embed("opckf0l87m", {
  videoFoam: true
});
</script>

<!--         </div> -->

    </div>
  </div>

  <div class="row text-center">
    <div class="small-10 columns small-centered">
      <div class="row">
        <div class="panel clearbg"></div>
      </div>
    </div>
  </div>
</div>
{% include navbar.html %}

<!-- Learn -->

{% assign section="code" %}

<div class="{{ section }}">
  <div class="fullheight"> 
  <div data-magellan-destination="{{ section }}" class="row" id="{{ section }}">
    <div class="small-12 columns panel">
      <div class="row">
        <div class="small-10 colums right">
          <h2>{% include icons/learnicon %}&nbsp;{{ section | capitalize }}</h2>
        </div>
      </div>
    </div>
  </div>
  
  <div class="row">
    <div class="small-12 columns text-center">
      {% include playerselect.html %}
    </div>
    </div>
  <!-- Learn Controls-->
  <div class="row text-center">
    <div class="small-9 small-centered columns show-for-medium-up">
      <ul class="button-group">
        <li><a onclick="{{ section }}Playlist.play(0,0)" class="button button-lg button-video">
          <i class="fa fa-play"></i>&nbsp;Pages</a>
        </li>
        <li><a onclick="{{ section }}Playlist.play(0,1)" class="button button-lg button-video">
          <i class="fa fa-play"></i>&nbsp;Elements</a>
          </li>
        <li><a onclick="{{ section }}Playlist.play(0,2)" class="button button-lg button-video">
          <i class="fa fa-play"></i>&nbsp;Attributes</a>
        </li>
      </ul>
    </div>
  </div>
</div>

<div class="row text-center trinket-area">
  <div class="small-10 small-centered columns">
    <h3>Get Hands-On Practice:</h3>
{% include trinket-open type='html' height='450' %}
{% include trinkets/learn-trinket %}
{% include trinket-close %}
    <h3>Done? Try Another Video Above!</h3>
  </div>
</div>

{% assign section="teach" %}
    
<!-- Teach Section -->
<div class="{{ section }}">
  <div class="fullheight">
  <div data-magellan-destination="{{ section }}" class="row" id="{{ section }}">
    <div class="small-12 columns panel rounded">
      <div class="row">
        <div class="small-10 colums right">
          <h2>{% include icons/teachicon %}&nbsp;{{ section | capitalize }}</h2>
        </div>
      </div>
    </div>
  </div>
    <div class="row">
    <div class="small-12 columns text-center">
      {% include playerselect.html %}
  </div>

  <!--{{ section }} Video Controls -->
     <div class="row text-center">
        <div class="small-9 small-centered columns show-for-medium-up">
        <ul class="button-group">
          <li><a onclick="{{ section }}Playlist.play(0,0)" class="button button-lg button-video">
          <i class="fa fa-play"></i>&nbsp;Pages</a>
          </li>
          <li><a onclick="{{ section }}Playlist.play(0,1)" class="button button-lg button-video">
          <i class="fa fa-play"></i>&nbsp;Elements</a>
          </li>
          <li><a onclick="{{ section }}Playlist.play(0,2)" class="button button-lg button-video">
          <i class="fa fa-play"></i>&nbsp;Attributes</a>
          </li>
        </ul>
       </div>
      </div>
      
  </div>
  </div>
   

<div class="row text-center trinket-area">
  <div class="small-10 small-centered columns">
    <h3>Give Your Students Hands-on Activities:</h3>
{% include trinket-open type='html' height='450' %}
{% include trinkets/teach-trinket %}
{% include trinket-close %}
    <h3>Want Lesson Ideas? Try Another Video Above!</h3>
  </div>
</div>
</div> 
{% assign section="share" %}

<!-- Share -->
<div data-magellan-destination="{{ section }}" class="row" id="{{ section }}">
  <div class="small-12 columns panel">
    <div class="row">
      <div class="small-10 colums right">
        <h2>{% include icons/shareicon %}&nbsp;{{ section | capitalize }}</h2>
      </div>
    </div>
  </div>
</div>

<!--Share call to actions -->
<div class="row text-center">
  <div class="small-10 small-centered columns">
    <div class="row  trinket-area">
      <h3>Know Anyone Else Who'd Like to Learn &amp; Teach HTML?</h3>
{% include trinket-open type='html' height='450' %}
{% include trinkets/share-trinket %}
{% include trinket-close %}
      <h3>Customize the Code Above Then Share the Link!</h3>
    </div>
    <div class="row" data-equalizer>
      <div class="small-12 medium-4 columns panel clearbg" data-equalizer-watch>
        <a href="http://twitter.com">
        <div class="clearbg panel" ><h3><i class="fa fa-twitter"></i><br>Tweet</h3></div>
        </a>
      </div>      
      <div class="small-12 medium-4 columns panel clearbg" data-equalizer-watch>
        <a href="http://facebook.com" onclick="{{ section }}Playlist.play(0,1)">
        <div class="panel clearbg"><h3><i class="fa fa-facebook"></i><br>Share</h3></div>
        </a>
      </div>
      <div class="small-12 medium-4 columns panel clearbg" data-equalizer-watch>
        <a href="http://plus.google.com" onclick="{{ section }}Playlist.play(0,2)">
        <div class="panel clearbg"><h3><i class="fa fa-google-plus"></i><br>+1</h3></div>
        </a>
      </div>
    </div>
  </div>
</div>



{% comment %}

{% assign section="contribute" %}

<!-- Contribute -->
<div class="row" id="contribute" data-magellan-destination="contribute">
  <div class="small-12 columns panel">
    <div class="row">
      <div class="small-10 colums right">
        <h2>Contribute</h2>
      </div>
    </div>
  </div>
</div>
<div class="row text-center">
  <div class="small-10 columns small-centered">
    <div class="row">
      <div class="panel clearbg">
        <a href="http://github.com">
          <div class="panel clearbg">
            <img src='/img/octoprof.jpg'>
          </div>
        </a>
      </div> 
    <div class="row">
      <div class="panel clearbg">
        <a href="http://github.com">
          <div class="panel clearbg">
            <h3>Have a good idea?<br>Contribute Code, Issues, or Suggestions on Github</h3>
          </div>
        </a>
      </div> 
    </div>
  </div>
</div>
</div>
{% endcomment %}