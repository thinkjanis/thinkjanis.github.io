---
layout: default
---
<section class="hero is-light is-medium">
  
  <div class="hero-body">
    <div class="container">
      <div class="content has-text-centered">

        <h2 class="subtitle is-home is-size-6 is-uppercase is-size-7-mobile">
          {{ site.landing_subtitle_one }}
        </h2>

        <h1 class="site-myname title has-text-weight-bold is-size-1-mobile">
          {{ site.myname }}
        </h1>

        <h2 class="subtitle is-home is-size-6 is-uppercase is-size-7-mobile">
            {{ site.landing_subtitle_two }}
        </h2>

        <a href="https://medium.com/@{{ site.handle }}" target="_blank">
          <span class="icon is-medium">
              <i class="fa fa-lg fa-medium"></i>
            </span>
        </a>
        
        <a href="https://angel.co/{{ site.handle }}" target="_blank">
          <span class="icon is-medium">
              <i class="fa fa-lg fa-angellist"></i>
            </span>
        </a>

        <a href="https://twitter.com/{{ site.handle }}" target="_blank">
          <span class="icon is-medium">
              <i class="fa fa-lg fa-twitter"></i>
            </span>
        </a>

      </div>
    </div>
  </div>

  <div class="hero-foot">
      <nav class="tabs is-centered">
        <div class="container">
          <ul>
            <li><a href="/about-me">About me</a></li>
            <li><a class="has-text-weight-semibold" href="/">My work</a></li>
            <li><a href="/contact-me">Contact me</a></li>
          </ul>
        </div>
      </nav>
    </div>

</section>

<section class="post-container m-vertical-1">
  <div class="container">
    <div class="columns is-multiline">

      {% for post in site.posts %}
        <div class="column is-half">
          <div class="card">
        
            <div class="card-image">
              <figure class="image is-16by9">
                <a href="{{ post.url | relative_url }}">
                  <img src="{{ post.imgurl }}" alt="{{ post.title }}">
                  <span class="tag is-dark">
                    {{ post.tag }}
                  </span>
                </a>
              </figure>
            </div>
            
            <div class="card-content has-text-centered p-1">
                <h3 class="is-uppercase is-size-7 has-text-weight-semibold">{{ post.title }}</h3>
            </div>

          </div>
        </div>
      {% endfor %}

    </div>
  </div>
</section>
