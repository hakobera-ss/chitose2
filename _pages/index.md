---
layout: defaults/page
permalink: index.html
narrow: true
title: Home
---

## Welcome to chitose.org

{% include components/intro.md %}

詳しくは[About]({{ site.baseurl}}{% link _pages/about.md %})へ

<br>



<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}

© 2020 hakobe some rights reserved ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.en)). Powered by [Jekyll](https://jekyllrb.com) & [Friday Theme](https://sfreytag.github.io/friday-theme/).

<div align=center><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a></div>