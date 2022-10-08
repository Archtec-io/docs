---
layout: default
title: Home
nav_order: 1
description: "Archtec Docs"
permalink: /
last_modified_date: "Sat , 08 Oct 2022 15:33:40 GMT"
---

# Archtec documentation.
{: .fs-9 }

Powered by Just-the-docs and Jekyll. Hosted on GitHub.
{: .fs-6 .fw-300 }

[Help us](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/Archtec-io/docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

{: .warning }
> This documentation is still **work in progress**.

---

## Links
[Mapserver](http://map.archtec.freemyip.com)
[Discord](https://discord.gg/txCMTMwBWm)
[GitHub](https://github.com/Archtec-io)
[Bugtracker](https://github.com/Archtec-io/bugtracker/issues)

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
