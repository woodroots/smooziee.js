---
layout: page
title: 概要
permalink: /about/
---

ページ内リンクのスムーススクロールに加えて、サイト内の他のページへのリンクの際もスムーススクロールできるjQueryプラグインです。

他ページへのリンクにハッシュタグが指定されている場合は、ページ遷移後に、ターゲット要素までスムーススクロールします。


## 機能

通常のページ内リンクスクロールでは、他のページへリンクした時にはスクロールせず、そのまま、ハッシュタグ（#）で指定した場所が表示されますが、 {{ site.title }}では、他ページへのリンクでハッシュタグ（#）を指定した場合、ページ遷移後にその地点までスクロールして表示します。

## 特長

よくあるスムーススクロールでは、ページ内リンクをしてもURLにハッシュタグが表示されなかったりすることがあります。{{ site.title }}では、ハッシュタグを表示させる、させないを設定で変更することができます。詳しくは<a href="{{ '/install-and-settings/' | relative_url }}">インストールと設定</a>をお読みください。

## サンプル

<a class="btn btn--primary" href="{{ '/sample-1.html' | relative_url }}">sample</a>