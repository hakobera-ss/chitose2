---
layout: defaults/page
permalink: index.html
narrow: true
title: Home
images:
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/967/535/original/32c57244b22db79e.png
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/760/016/original/99a1471f45629999.png
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/735/191/original/6aad6dceb0c12171.jpeg
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/629/393/original/a250c6375635920c.png
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/539/091/original/6130fcc07122fd6f.jpg
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/497/594/original/25228234871c63f7.jpg
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/284/971/original/9caba3d88bd2102d.png
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/257/557/original/b054c5bff66bff84.jpg
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/199/457/original/618063a73a5352b8.jpg
  - https://s3-ap-northeast-1.amazonaws.com/felesitas.cloud.storage/media_attachments/files/002/199/807/original/3d347372be6a31fb.jpg
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