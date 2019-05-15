---
layout: page
---
<br>
<div class="col-12">
<h3 class="title-3 text-dark mb-4">Recent projects</h3>
</div>

<div class="container pb-6">
    <div class="row">
      {% for project in site.data.projects %}
        <div class="col-12 col-md-6 mb-2 ">
            <div class="card">
                {% if project.image %}<a href="{{project.url}}">
                <img class="card-img-top img-fluid" src="{{project.image}}" alt="{{ project.title }}">
                <div class="card-body">
                    <h5 class="card-title">{{ project.title }}</h5>
                    <p class="card-text">{{ project.text}}</p>
                    <p class="card-text"><small class="text-muted">{{ project.sometitle }}</small></p>
                </div>
                </a> {% endif %}
            </div>
        </div>
          {% endfor %}
    </div>
</div>


<div class="container pt-5 pb-5 pt-md-7 pb-md-7">

  <div class="row justify-content-center">
    <div class="col-12">
      <h3 class="title-3 text-dark mb-4">Videos</h3>
    </div>
    {% for feature in site.data.features %}
    <div class="col-12 col-md-6 col-lg-4 mb-2">
      <!-- <div class="feature"> -->
        {% if feature.image %}<div class="feature-image"><a href="{{feature.youtube}}"><img alt="{{ feature.title }} logo" src="{{ feature.image }}" /></a></div> {% endif %}
        <h4 class="feature-title">{{ feature.title }}</h4>
        <div class="feature-content">{{ feature.description }}</div>
      <!-- </div> -->
    </div>
    {% endfor %}
  </div>
</div>
