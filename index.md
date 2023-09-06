---
layout: default
title: Home
---

Long ago, the world was broken. A teeming planet broke, and only the Shielded survived. Protected by domes of arcane magic, small zones remain as the only livable oases. Each bubble of civilization has its own story for the cataclysm that wrecked the world and the origin of the shields that protect them. Each is as different and varied as the culture that has evolved within it, sheltered from the Aberrant Wastes.

_Welcome to the Shattered Realm._

In a dangerous world, few venture beyond their home oasis. There are, however, a handful of rare individuals that step beyond. The Ambassador’s Guild, based in the compact city of Haven, is home to such adventurers. The guild facilitates what limited communication there is between these disparate worlds, trading in information and rarities.

## The Shielded

There are many pockets of civilization shielded by magic, but some have been disconnected from the greater world since the beginning. Others have closer connections, driven by trade and ties to the guild. Here are the best known, though certainly not the only.

<ul class="shields">
{% for shield in site.shields %}
<li><a href="{{ shield.url }}">
<img src="/images/{{ shield.title }}.jpeg" alt="">
{{ shield.title }}</a></li>
{% endfor %}
</ul>