---
layout: default
section: trinket-player
---

<div class="off-canvas-wrap {{ section }}" data-offcanvas>
<div class="inner-wrap fullheight"> 
<nav class="tab-bar">
    <section class="right-small">
    <a class="right-off-canvas-toggle menu-icon" href="#"><span></span></a>
    </section>

    <section class="middle tab-bar-section text-right">
    <a class="right-off-canvas-toggle"><h1 class="title">Browse Trinkets</h1></a>
    </section>
    <section class="left tab-bar-section text-left"><img src="http://trinket.io/img/trinket-logo-big.png"></section>
  </nav>
<!-- Page Content -->
<div class="row text-center trinket-player">
  
  <div class="small-10 small-centered columns">
    <h3>Get Hands-On Practice:</h3>
{% include trinket-open type='html' height='450' %}
{% include trinkets/learn-trinket %}
{% include trinket-close %}
    <h3>Done? Grab a Trinket from the Menu on the Right!</h3>
  </div>
</div>

<!-- Left Off Canvas Menu -->
 <div class="right-off-canvas-menu" id="{{ section }}menu">
     <ul class="off-canvas-list">
        <li><label>Trinkets</label></li>
        <li><a href="#">A Cool Trinket Demonstrating HTML</a></li>
        <li><a href="#">A Cool Trinket Demonstrating HTML</a></li>
        <li><a href="#">A Cool Trinket Demonstrating HTML</a></li>
        <li><a href="#">A Cool Trinket Demonstrating HTML</a></li>
        <li><a href="#">A Cool Trinket Demonstrating HTML</a></li>
        <li><a href="#">...</a></li>
        <li><label>Teach HTML?</label></li>
        <li><a href="#">Create a Free Trinket Account</a></li>
        <li><label>Other Trinket Types:</label></li>
        <li><a href="#">PythonL</a></li>
        <li><a href="#">LaTeX</a></li>
        <li><a href="#">Music</a></li>
      </ul>
  </div>  
    
    <a class="exit-off-canvas"></a>
  </div>
</div>