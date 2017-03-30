---
layout: post
title: Developing Threat
date: 2017-03-22 21:00:00
categories: arma3 events
tags: media debrief stratis
author: Laterna
mission-maker: sotkork
---


**Συναγερμός** σημάνει σε αμερικανική στρατιωτική βάση. Εχθρικό πυροβολικό έχει αναπτυχθεί σε θέση ικανή να βάλει κατά της θέσης μας. Άμεση εκκένωση με εναέρια μέσα και αναδιοργάνωση σε προωθημένη βάση. 

Οι στόχοι οι εξής, κατάληψη της εχθρικής βάσης και εξουδετέρωση τριών θέσεων. Αποθήκης πυρομαχικών, της θέσεως του πυροβολικού και της κεραίας επικοινωνιών.

{% assign dateformatted = page.date | date: "%d-%m-%Y" %}
{% assign imgpath =   page.date | date: "%d-%m-%Y" %}
{{ imgpath }}

{{ dateformatted }}

<div>
{% for myimage in site.static_files | where: "image", true %}
  {% if myimage.path contains  dateformatted %}
    <img class="screenshot ingame" src="{{ myimage.path }}">
  {% endif %}
{% endfor %}
</div>