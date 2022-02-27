---
title: "Splash Page"
layout: splash
permalink: /splash-page/
date: 2016-03-23T11:48:41-04:00
header:
header:
  overlay_image: https://upload.wikimedia.org/wikipedia/commons/b/bd/Wall_street_of_the_tombs_sacred_way_Kerameikos_Athens.jpg
  caption: "iDEIA ÉTICA"
  overlay_color: "#000"
  overlay_filter: "0.5"
  caption: "iDEIA ÉTICA"
  actions:
    - label: "Últimas Publicações"
      url: "https://ietica.github.io/posts/"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: https://upload.wikimedia.org/wikipedia/commons/6/65/Laughing_kookaburra_%289115601110%29.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: https://upload.wikimedia.org/wikipedia/commons/7/75/Blue-winged_kookaburra_arp.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: https://upload.wikimedia.org/wikipedia/commons/b/bd/Dacelo_novaeguineae%2C_Swanbourne.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: https://upload.wikimedia.org/wikipedia/commons/d/d8/Galah._%28Eolophus_roseicapilla%29_%2811179413123%29.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: https://upload.wikimedia.org/wikipedia/commons/4/48/Angel_at_Centennial_Park_Conservatory.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: https://upload.wikimedia.org/wikipedia/commons/8/84/Cacatua_haematuropygia_Parc_des_Oiseaux_21_10_2015_1.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
