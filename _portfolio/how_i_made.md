---
title: "How I Built and Hosted My  Website with Jekyll and GitHub Pages"
excerpt: "(Work In Progress) In this article, I explain how I built my own website using the Minimal Mistakes Jekyll theme and hosted it (for free) on GitHub Pages." 
header:
#   image: /assets/images/360X/IMG_5658_cropped.jpg
  teaser: assets/images/site_redesign/ipad1.png

sidebar:
  - title: "Roles"
    image: /assets/images/site_redesign/Ink_Blot_logo_splat.png
    image_alt: "Ink Blot Media Group Inc."
    text: "Designer, Report Writer"

  - title: "Responsibilities"
    text: "Created wireframes for a site redesign"

old_site:
  - url: /assets/images/site_redesign/old2.jpg
    image_path: assets/images/site_redesign/old2.jpg
    alt: "Old site home page"

  - url: /assets/images/site_redesign/image6.png
    image_path: assets/images/site_redesign/image6.png
    alt: "Old site store page"

  - url: /assets/images/site_redesign/old4.png
    image_path: assets/images/site_redesign/old4.png
    alt: "Old site videos page"

wf_site:
  - url: /assets/images/site_redesign/splash_page_wf.png
    image_path: assets/images/site_redesign/splash_page_wf.png
    alt: "Wireframe of new splash page"

  - url: /assets/images/site_redesign/store_page_wf.png
    image_path: assets/images/site_redesign/store_page_wf.png
    alt: "Wireframe of new store page"
    
  - url: /assets/images/site_redesign/videos_page_wf.png
    image_path: assets/images/site_redesign/videos_page_wf.png
    alt: "Wireframe of new videos page"

  - url: /assets/images/site_redesign/prod_page_wf.png
    image_path: assets/images/site_redesign/prod_page_wf.png
    alt: "Wireframe of new product page"

  - url: /assets/images/site_redesign/photo_gallery_wf.png
    image_path: assets/images/site_redesign/photo_gallery_wf.png
    alt: "Wireframe of new photo gallery page"

  - url: /assets/images/site_redesign/ipad1.png
    image_path: assets/images/site_redesign/ipad1.png
    alt: "I used Mockup for iPad to create the wireframes"
last_modified_at: 2021-09-27 17:44:00

---
<p align="center">
  <a href="{{ site.url }}{{ site.baseurl }}/assets/images/site_redesign/ipad_pic.jpg">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/images/site_redesign/ipad_pic.jpg" alt="picture of iPad" width="400" style="border-radius:10px" />
  </a>
</p>

This site that you are currently reading this article on was built by me! Since I wanted to market myself as a web developer and a UX Designer, I decided to build my own website instead of using something like uxfolio. I wanted something that I could host for free that wouldn't have too many parts too it so I could easily maintain it and add content to it.


## Why I Chose Jekyll


With so many ways to build a website available for me to learn, I had to choose one that would fit my needs. I have experience using Node.Js with Express and MongoDB for building a website in a web development course that I took in 2018, but there were a few issues with that.

First, it felt like building it with Node  would be a bit too much for a simple portfolio site with static content. I know that I don't have to build this website with things like account creation or cookies. I also knew that GitHub pages doesn't support JavaScript frameworks like Node since it really is meant for static content.

While it would definitely have been good practice, I decided to go with something simpler.


## Enter Jekyll. 


> Jekyll is the engine behind GitHub Pages, a GitHub feature that allows users to host websites based on their GitHub repositories for no additional cost. Jekyll can be used in combination with front-end frameworks such as BootStrap, Semantic UI and many others.

That is Wikipedia's description of Jekyll. In short, GitHub Pages allows you to host static websites for free and Jekyll can be used to convert Markdown into HTML for static websites. While Jekyll may not be all that useful for webapps, its lightweight and easy-to-use nature make it perfect for small static sites like personal blogs.

*TODO: Add image here*

Another thing that makes Jekyll great is how easy it is to apply a theme for your site and make it look and feel good from the get go. For example, this site uses the free and open-source Minimal Mistakes theme made by Michael Rose.

You can easily find a free theme that suits your needs and your tastes. Plus, there are also paid themes that you can use for your site. Giving you even more options while also being able to support developers.

*TODO: Plan outline.*


> Hi. If you are reading this, then thank you! I am currently in the process of  writing this article so it is incomplete.
 In case you are curious, below are a few lines detailing a rough idea I have for what I want to put
in this article.

---

Talk about how lightweight it is so I can make new articles fairly easily. 
I can compile and run a jekyll site with underpowered hardware. 
I can edit it directly on GitHub using GitHub.dev. 
I can even edit the code remotely using my 2nd PC at home. 
Then I can use SSH tunneling with through an app to access that PC's localhost so I can preview the site on Safari for iPad.
It really is super cool. It has a lot of features. Minimal Mistakes is awesome. 
There was a learning curve but once I sat down and devoted time to learning it I was able to build this site and add content.
>
