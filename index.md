---
permalink: /
title: Scanleft Blog
---

<header>
  <h1><a href="https://github.com/scanleft/" title="View Guido's GitHub profile page">Guido Hoermann</a></h1>
</header>

<article>
  <p>Find me on <a href="https://github.com/scanleft/" title="Guido on GitHub">GitHub</a> and <a href="https://twitter.com/scanleft" title="Guido on Twitter">Twitter</a>.</p>

  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</article>
