---
layout: default
---

  <div class="row text-center bluebg">
    <div class="small-10 columns small-centered">
      <div class="row">
        <div class="panel clearbg">    
        <div class="slider">
          <div>
          {% include trinket-open type="html" %}
          {% include trinkets/learn-trinket %}
          {% include trinket-close type="html" %}
          </div>
          
          <div>
          {% include trinket-open type="html" %}
          {% include trinkets/teach-trinket %}
          {% include trinket-close type="html" %}
          </div>
          <div>
          {% include trinket-open type="html" %}
          {% include trinkets/share-trinket %}
          {% include trinket-close type="html" %}
          </div>
        </div>
        <div class="button" onclick="$('.slider').slickGoTo(1)">2</div>
        <div class="button" onclick="$('.slider').slickGoTo(2)">2</div>
        <div class="button" onclick="$('.slider').slickGoTo(3)">2</div>
        </div>
      </div>
    </div>
  </div>