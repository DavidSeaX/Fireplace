---
title: "Welcome"
permalink: /
layout: splash
author_profile: false

header:
  overlay_color: "#ffa77b9c"
#  overlay_filter: "0.5"
#  overlay_color: "#000"
  overlay_filter: linear-gradient(45deg, rgba(255, 60, 0, 0.75), rgba(81, 81, 81, 0.8))
#  overlay_image: /assets/img/banner/???.jpg
  actions:
    - label: "Welcome"
      url: "#main"
#  caption: "<a href='https://???'>&copy;</a>"
  excerpt: "&nbsp;"

intro: 
  - excerpt: "&nbsp;"

# feature_row:
#  - image_path: "/assets/img/feature/table.jpg"
#    alt: "&copy; https://???"
#    image_caption: ""
#    title: ""
#    excerpt: ""
#    url: "/???"
#    btn_label: "Read"
#    btn_class: "btn--light-outline"
#  - image_path: assets/images/boat.jpg
#    alt: "???"
#    title: "???"
#    excerpt: "???"
#    url: "???"
#    btn_label: "???"
#    btn_class: "btn--primary"

#  - image_path: /assets/images/???.jpg
#    image_caption: "&copy;"
#    alt: "placeholder image 2"
#    title: "???"
#    excerpt: "???"

#feature_row2:
#  - image_path: /assets/img/feature/???.jpg
#    alt: "@copy; https://???"
#    image_caption: "<a href='https://???'>&copy;</a>"
#    title: "???"
#    excerpt: '???'
#    url: "#???"
#    btn_label: "???"
#    btn_class: "btn--light-outline"
#feature_row3:
#  - image_path: /assets/images/???.jpg
#    image_caption: "<a href='???'>&copy;</a>"
#    alt: "???"
#    title: "???"
#    excerpt: ''
#    url: "#???"
#    btn_label: "???"
#    btn_class: "btn--light-outline"
#feature_row4:
#  - image_path: /assets/images/???.jpg
#    alt: "placeholder image 2"
#    title: "Placeholder Image Center Aligned"
#    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% comment %}
{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
{% endcomment %}
