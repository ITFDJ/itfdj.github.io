---
layout: page
title: IMAGINE THE FLOOR. &#35;ITF_DJ について
permalink: /about/
---

<div class="center" markdown="1">
[![IMAGINE THE FLOOR. の遊び方](/images/howtoitf_header.png)](/howtoitf.html)
</div>

フロアで出会う、新しい自分 --- 普段はつくば市天久保1丁目のクラブ [OctBaSS](https://twitter.com/octbass_tsukuba) でクラブイベントを行っている「**IMAGINE THE FLOOR.**」の公式ウェブサイトです。

クラブ初心者の人も気軽に足を運べるオールジャンルイベントです。好評につき定期イベントに昇格しました。

番外編イベントとして、つくば市天久保3丁目のピザ屋さん [ピッツェリア レガーメ](http://www.pizzerialegame.com/) にて「**IMAGINE THE PIZZA. #ITP_DJ**」も行っていました。

{% if site.events.upcoming %}
<div id="upcoming" class="upcoming" markdown="1">

# 開催予定

- [{{ site.events.upcoming.name }} ({{ site.events.upcoming.date | date: "%Y-%m-%d" }})]({{ site.events.upcoming.url }})

</div>
{% endif %}

<div class="archives" markdown="1">

# 過去の開催

TwiPla やアップロードされた mix などへのリンクをまとめています。

{% for ev in site.events.archives reversed %}
- [{{ ev.name }} ({{ ev.date | date: "%Y-%m-%d" }})]({{ ev.archive | prepend: '/archives/' | prepend: site.baseurl }}){% endfor %}

</div>

## Twitter

### 公式アカウント: [@ITF_DJ](https://twitter.com/ITF_DJ)

<a class="twitter-timeline" href="https://twitter.com/ITF_DJ" data-widget-id="574970988124762112">@ITF_DJさんのツイート</a>

### ハッシュタグ: [#ITF_DJ](https://twitter.com/search?q=%23ITF_DJ)

<a class="twitter-timeline" href="https://twitter.com/hashtag/ITF_DJ" data-widget-id="574971387170852864">#ITF_DJ のツイート</a>

関連: [#ITP_DJ](https://twitter.com/search?q=%23ITF_DJ)

<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>

## Mixcloud アカウント

[IMAGINE THE FLOOR. #ITF_DJ \| Mixcloud](https://www.mixcloud.com/ITF_DJ/)

<iframe width="200" height="250" src="https://www.mixcloud.com/widget/follow/?u=https%3A%2F%2Fwww.mixcloud.com%2FITF_DJ%2F&dark=1" frameborder="0"></iframe>

## USTREAM チャンネル

[USTREAM: IMAGINE THE FLOOR.](http://www.ustream.tv/channel/itf-dj)

## Facebook ページ

<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/ja_JP/sdk.js#xfbml=1&version=v2.0";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<div class="fb-like-box" data-href="https://www.facebook.com/pages/IMAGINE-THE-FLOOR/327942300690291" data-colorscheme="dark" data-show-faces="false" data-header="true" data-stream="true" data-show-border="true"></div>

## パーティフォト

[![パーティフォト](/images/pf_banner.jpg)](/photo.html)
