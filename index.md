---
layout: default
title: Home
nav_order: 1
description: "Archtec Docs"
permalink: /
---

# Archtec documentation.
{: .fs-9 }

Powered by Just-the-docs an Jekyll. Hosted on GitHub.
{: .fs-6 .fw-300 }

[Help us](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/Archtec-io/docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

{: .warning }
> This documentation is still work in progress!

## Getting started

### Dependencies

Just the Docs is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [Jekyll quick start guide](https://jekyllrb.com/docs/) for more information. Just the Docs requires no special plugins and can run on GitHub Pages' standard Jekyll compiler. The [Jekyll SEO Tag plugin](https://github.com/jekyll/jekyll-seo-tag) is included by default (no need to run any special installation) to inject SEO and open graph metadata on docs pages. For information on how to configure SEO and open graph metadata visit the [Jekyll SEO Tag usage guide](https://jekyll.github.io/jekyll-seo-tag/usage/).

---

## About Archtec

Archtec is &copy; 2021-{{ "now" | date: "%Y" }} by Niklp.

### License

This documentation is distributed by an [MIT license](https://en.wikipedia.org/wiki/MIT_License).

### Contributing

Just fork this repo and make a PR.

#### Thank you to the contributors of Archtec docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
