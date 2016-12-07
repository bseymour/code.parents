---
title: "Vanilla Title"
custom_title: "Custom Title for SEO"
layout: splash
permalink: /index.html
date: 2016-01-12T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /images/unsplash-nasa.jpg
  caption: "My Caption"
excerpt: "• excerpt 1<br/>
          • excerpt 2<br/>
          • excerpt 3<br/>
          • excerpt 4<br/>
          • excerpt 5"
intro:
  - excerpt: '** Intro message - probably news or current ***'
feature_row:
  - image_path: feature1-image-th.jpg
    alt: "Alt1"
    title: "Feature 1 Title"
    excerpt: "Feature 1 excerpt"
    url: "http://google.co.uk"
    btn_label: "Go To Ext Site"
    btn_class: "btn--inverse"
  - image_path: feature2-image-th.jpg
    alt: "Alt2"
    title: "Feature 2 Title"
    excerpt: "Feature 2 excerpt"
    url: "/directory/"
    btn_label: "Go To internal link"
    btn_class: "btn--inverse"
  - image_path: feature3-image-th.jpg
    alt: "Alt3"
    title: "Feature 3 Title"
    excerpt: "Feature 3 excerpt"
    url: "http://google.co.uk"
    btn_label: "Go To Ext Site"
    btn_class: "btn--inverse"
feature_row2:
  - image_path: Feature2-1-th.jpg
    alt: "Feature2-1"
    title: "Feature2-1"
    excerpt: 'Feature2-1 ... longer words....'
    url: "/directory"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row3:
  - image_path: feature3-11-image-th.jpg
    alt: "Alt3-1"
    title: "Feature 3-1 Title"
    excerpt: "Feature 3-1 excerpt"
    url: "http://google.co.uk"
    btn_label: "Go To Ext Site"
    btn_class: "btn--inverse"
  - image_path: feature2-image-th.jpg
    alt: "Alt3-2"
    title: "Feature 3-2 Title"
    excerpt: "Feature 3-2 excerpt"
    url: "/directory/"
    btn_label: "Go To internal link"
    btn_class: "btn--inverse"
  - image_path: feature3-3-image-th.jpg
    alt: "Alt3-3"
    title: "Feature 3-3 Title"
    excerpt: "Feature 3-3 excerpt... with no CTA"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" %}
