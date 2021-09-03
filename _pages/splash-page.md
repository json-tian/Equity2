---
title: "Equity Lighthouse"
layout: splash
permalink: /
date: 2020-04-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
hook: "Our mission is to share investment knowledge, conduct economic discussions and provide practices for students interested in capital markets."
intro: 

feature_row2:
  - image_path: assets/images/report.jpg
    alt: "placeholder image 1"
    title: "Reports"
    excerpt: "Annual reports and monthly sector reports."
    url: "/reports/"
    btn_label: "View Reports"
    btn_class: "btn--primary"

feature_row3:
  - image_path: assets/images/thought.jpg
    alt: "placeholder image 2"
    title: "Thought Pieces"
    excerpt: "Join us for a weekly discussion on world issues."
    url: "/thoughtpieces/"
    btn_label: "View Thought Pieces"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}