---
title: "Hi! (Work in progress)"
layout: single
permalink: /
date: 2021-06-19
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: 'https://dm0qx8t0i9gc9.cloudfront.net/watermarks/image/rDtN98Qoishumwih/work-in-progress_zJ6mkuuu_SB_PM.jpg'
  actions:
    - label: "View My Portfolio"
      url: "/portfolio/"
  caption: "Photo credit: [**Storyblocks**](https://storyblocks.com)"
excerpt: "Welcome to my website! I am a UX Designer and Web Developer based in Tallahassee, Florida. Take a look at some of my previous projects. You'll probably find some of them quite interesting!"


intro: 
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    title: "This website is a work in progress."
    excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque.'
    url: "/cv/"
    btn_class: "btn--primary"
    btn_label: "Curriculum Vitae"


feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Baz Boom Identity"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/portfolio/baz-boom-identity/"
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

  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Foo Bar Website"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/portfolio/foo-bar-website/"
    btn_class: "btn--primary"
    btn_label: "Learn more"

---

{% include feature_row id="intro" type="left" %}


{% include feature_row %}
