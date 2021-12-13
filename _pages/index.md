---
title: "AI@Sheffield"
layout: splash
permalink: /
excerpt: "Artificial intelligence and data science<br>at the University of Sheffield"
header:
  overlay_image: /assets/images/banner.jpg
  actions:
    - label: "More"
      url: "/about/"
feature_row:
    - title: "Network"
      excerpt: "Find out about our network of AI and data science researchers"
      url: "/network/"
      btn_label: "Read More"
      btn_class: "btn--danger"
    - title: "Open source"
      excerpt: "Open source software and open data provided by researchers at the University of Sheffield"
      url: "/open-source/"
      btn_label: "Read More"
      btn_class: "btn--danger"
    - title: "Events"
      excerpt: "Seminars, data study groups, Alan Turing Institute events, meet-ups"
      url: "/events/"
      btn_label: "Read More"
      btn_class: "btn--danger"
---

Tempor velit sint sunt ipsum tempor enim ad qui ullamco. Est dolore anim ad velit duis dolore minim sunt aliquip amet commodo labore. Ut eu pariatur aute ea aute excepteur laborum. Esse ea esse excepteur minim mollit qui cillum excepteur ex dolore magna. Labore deserunt fugiat incididunt incididunt sint ea. Consequat dolore aute laboris quis proident quis non et est consectetur ex eiusmod sit culpa.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

{% include feature_row %}

Tempor velit sint sunt ipsum tempor enim ad qui ullamco. Est dolore anim ad velit duis dolore minim sunt aliquip amet commodo labore. Ut eu pariatur aute ea aute excepteur laborum. Esse ea esse excepteur minim mollit qui cillum excepteur ex dolore magna. Labore deserunt fugiat incididunt incididunt sint ea. Consequat dolore aute laboris quis proident quis non et est consectetur ex eiusmod sit culpa.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

Nulla deserunt eiusmod, est sunt veniam legam laborum. Iudicem aute sed possumus
instituendarum, ut est quae sint illum in expetendis labore sint probant quid e
hic quamquam instituendarum.

<div class="feature__wrapper__no__lines">
  <div class="feature__item">
    <div class="archive__item">
      <div class="archive__item-body">
          <h2>Twitter</h2>
          <div class="archive__item-excerpt">
          <a class="twitter-timeline" data-height="500" data-theme="dark" href="https://twitter.com/haipinglu?ref_src=twsrc%5Etfw">Tweets by haipinglu</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
          </div>
      </div>
    </div>
  </div>
  <div class="feature__item">
    <div class="archive__item">
      <div class="archive__item-body">
          <h2>Latest news</h2>
          <div class="archive__item-excerpt">
          {% assign post = site.news.last %}
          <a href="{{ post.permalink }}">{{ post.title }}</a>
          <p>{{ post.excerpt }}</p>
          </div>
      </div>
    </div>
  </div>
  <div class="feature__item">
    <div class="archive__item">
      <div class="archive__item-body">
          <h2>Latest publication</h2>
          <div class="archive__item-excerpt">
          {% assign post = site.publications.last %}
          <a href="{{ post.permalink }}">{{ post.title }}</a>
          <p>{{ post.excerpt | truncate 200 }}</p>
          </div>
      </div>
    </div>
  </div>
</div>
