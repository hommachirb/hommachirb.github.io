---
layout: default
title:  コミュニティについて
---

![hommachirb]({{ site.baseurl }}/assets/img/hommachirb.png)

Ruby(プログラミング)初心者・未経験者

* Rubyに興味がある、勉強したい、けれど何から勉強すればいいのかわからない方
* 1人で勉強するのが不安で、足がかりになるような機会や場所がほしい方
* 既存のRUBYコミュニティに興味はあるが、初心者で参加するのは怖い方
* IT知識なしにIT会社で働いているのでIT知識をつけたい方
* プログラミングをこれから始めてみたい方

スタッフも未経験者・初心者ばかりなので共に成長していきましょう(^^)/
コーチとしてRubyについて教えて下さる方も大歓迎です(^-^)

----

<h3>イベント</h3>
{% for post in site.posts %}
<p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> <span class="text-muted">{{ post.date | date: "%B %-d, %Y" }}</span></p>
{% endfor %}
