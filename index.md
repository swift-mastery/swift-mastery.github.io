---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/bench-accounting-C3V88BOoRoM-unsplash.jpg
  actions:
    - label: "Learn More"
      url: "#training"
  caption: "Photo by [Bench Accounting](https://unsplash.com/@benchaccounting?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [**Unsplash**](https://unsplash.com)"
excerpt: "Your Path to Swift Mastery"
intro: 
  - excerpt: 'Learn advanced Swift topics from experts through in-person courses. 
    We covers topics including scalable / maintenable application architecture, performance,
    protocol-oriented design, server-side Swift, SwiftUI & Combine framework, and more.'
why_swift:
  - title: "Why Learn Swift In-Depth"
    excerpt: 'With Swift 5, the language is getting to a new level. Thanks to progressive disclosure, the
    language is easy to get started with. It is now multi-platform and can run both on iOS devices, on MacOS,
    but also on the server-side on Linux. However, the language is extremely dense and rich, as as you start
    getting to more complex topics, it can become quite overwhelming.'
    url: "/why/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="why_swift" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}