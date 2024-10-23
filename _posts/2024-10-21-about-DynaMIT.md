---
title: About the DynaMIT project
description: Learn more about our project
background:
  img: /assets/theme/images/Logo.png
  #href: https://unsplash.com/photos/XA1pHcB5AMA
#author: []
tags: []
custom_css: |
  .header {
      background-image: url('/assets/theme/images/Logo.jpg');
      # background-size: contain; /* Ensures the entire logo is visible */
      background-size: contain;
      background-position: center;
      height: 800px;
  }
  .header::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(0, 0, 0, 0.3); /* Semi-transparent black */
    z-index: 1;
  }

  .header h1, .header p {
    position: relative;
    z-index: 2;
    color: white; /* Ensures text stays on top of the overlay */
  }
---

<style>
{{ page.custom_css }}
</style>

Write a longer description about DynaMIT here???
