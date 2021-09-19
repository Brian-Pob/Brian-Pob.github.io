---
title: "Hi! (Work in progress)"
layout: single
permalink: /
date: 2021-06-19
# author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: 'https://dm0qx8t0i9gc9.cloudfront.net/watermarks/image/rDtN98Qoishumwih/work-in-progress_zJ6mkuuu_SB_PM.jpg'
  # actions:
  #   - label: "View My Portfolio"
  #     url: "/portfolio/"
  caption: "Photo credit: [**Storyblocks**](https://storyblocks.com)"
excerpt: "Welcome to my website! I am a UX Designer and Web Developer based in Tallahassee, Florida. Take a look at some of my previous projects. You'll probably find some of them quite interesting!"

about_me: 
  - image_path: assets/images/360X/methodology.jpg
    title: "Portfolio Projects"
    excerpt: 'On my portfolio page, you will find links to blog posts detailing my various projects. I believe you will find some of them interesting!'
    url: "/portfolio/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

intro: 
  - image_path: assets/images/cert-uxbeginner.jpg
    title: "Curriculum Vitae (CV)"
    excerpt: 'Take a look at some of my skills and accmomplishments on my CV page! Here, you can find my educational background, my work history, and a list of some of my projects.'
    url: "/cv/"
    btn_class: "btn--primary"
    btn_label: "Learn More"


feature_row:
  - image_path: assets/images/360X/IMG_5658_cropped.jpg
    alt: "360X Research Paper"
    title: "360X Research Paper"
    excerpt: "360X: A Research through Design (Rtd) Approach in the Design of a 360-Video Platform Interface"
    url: "/portfolio/360x/"
    btn_class: "btn--primary"
    btn_label: "Learn more"

  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Fizz Bang Identity"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/portfolio/fizz-bang-identity/"
    btn_label: "Read More"
    btn_class: "btn--primary"


---

{% include feature_row id="about_me" type="right" %}

{% include feature_row id="intro" type="left" %}

{% include feature_row %}
