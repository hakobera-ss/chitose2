---
layout: defaults/page
permalink: index.html
narrow: true
title: Home
images:
  - https://pixelfed.tokyo/storage/m/_v2/167071676260028416/f98697a52-a34568/XU72Vy6pTzHc/ta4Hk1SsIG2UGN0MgVXLXObOBqmLGw4YlfCBTkFP.jpg
  - https://pixelfed.tokyo/storage/m/_v2/167071676260028416/b84b52654-1eb8f9/d7uEPsMsWrYP/hHDEXJWiePgoXWYMtvfgGJCndZBbbZ2WHlQDptuL.jpg
  - https://pixelfed.tokyo/storage/m/_v2/167071676260028416/b84b52654-1eb8f9/Uf3TweBlNHlh/sPrbyQj8aNN340p1748Uc1Q4tHSxUK2pBgmTEEtS.jpg
  - https://pixelfed.tokyo/storage/m/_v2/167071676260028416/b84b52654-1eb8f9/NpDuA4emfR5R/fHfLzYeimPUFLC3VEAEkncQ8mc9Q7rC3hqehC9Lx.jpg
  - https://pixelfed.tokyo/storage/m/_v2/167071676260028416/222ce2dde-c74ca4/vMapr0zoH2HY/NxjSqLgKoZhUDFhgiWKxum42XdCw15zcfDp3RKcB.jpg
  - https://pixelfed.tokyo/storage/m/_v2/167071676260028416/8fb78bfd7-ec88b5/s3NQJ3Dm0S6w/2QdUVTlJS2lvrcETeRJMxHVQOkUl3xT5qvS8JRyX.jpeg
  - https://pixelfed.tokyo/storage/m/d6eeff88aa0c9af7fd5f87cd6431a14d929d049b/80fba949709b3d19a566cf4e148f4612cdab1cdd/JBU9Mp5y3fm28TthGXF6jcRKURigcJ8bcPWRyE7d.jpeg
---

## Welcome to chitose.org

<br>

<div align="center">
<div class="card border-0" style="width: 40rem;">
<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-100" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
</div>
</div>

<br>

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