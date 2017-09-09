---
layout: default
---
<section class="hero is-light is-medium">
  <div class="hero-body">
    <div class="container">
      <div class="content has-text-centered">
        <h2 class="subtitle is-6">Hi there! My name is</h2>
        <h1 class="title is-1">
          Janis Solks
        </h1>
        <h2 class="subtitle is-6">Digital media nerd blogging about tech</h2>
      </div>
    </div>
  </div>

  <div class="hero-foot">
      <nav class="tabs is-centered">
        <div class="container">
          <ul>
            <li><a>About me</a></li>
            <li class="is-active"><a>My work</a></li>
            <li><a>Contact me</a></li>
          </ul>
        </div>
      </nav>
    </div>
</section>

<section>
  <div class="container">
    <div class="columns is-multiline">
      {% for post in site.posts %}
        <div class="column is-half">
          <a href="{{ post.url | relative_url }}">
            <figure class="image is-16by9">
              <img src="/img/{{ post.slug }}.png">
            </figure>
          </a>
        </div>
      {% endfor %}
    </div>
  </div>
</section>