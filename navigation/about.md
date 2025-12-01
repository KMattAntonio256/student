---
layout: post
title: About
permalink: /about/
comments: true
---

## As a Conversation Starter

Here are some places I have lived.

<comment>
Flags are made using Wikipedia images
</comment>

<style>
    /* Updated styles: cleaner spacing, soft shadows, rounded corners for fun*/
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
        gap: 15px;
        margin-top: 15px;
    }
    .grid-item {
        text-align: center;
        padding: 10px;
        background: #fafafa;
        border-radius: 12px;
        box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        transition: transform 0.15s ease, box-shadow 0.15s ease;
    }
    .grid-item:hover {
        transform: translateY(-4px);
        box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    }
    .grid-item img {
        width: 100%;
        height: 100px;
        object-fit: contain;
        border-radius: 6px;
    }
    .grid-item p {
        margin: 6px 0;
        font-size: 0.95rem;
    }

    .image-gallery {
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
        gap: 12px;
        padding: 10px 0;
    }
    .image-gallery img {
        max-height: 160px;
        border-radius: 10px;
        box-shadow: 0 2px 6px rgba(0,0,0,0.12);
        flex-shrink: 0;
    }
</style>

<div class="grid-container" id="grid_container"></div>

<script>
    var container = document.getElementById("grid_container");
    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";

    var living_in_the_world = [
        {"flag": "0/01/Flag_of_California.svg", "greeting": "Hey", "description": "California - Since forever"}
    ];

    for (const location of living_in_the_world) {
        var gridItem = document.createElement("div");
        gridItem.className = "grid-item";

        var img = document.createElement("img");
        img.src = http_source + location.flag;
        img.alt = location.flag + " Flag";

        var description = document.createElement("p");
        description.textContent = location.description;

        var greeting = document.createElement("p");
        greeting.textContent = location.greeting;

        gridItem.appendChild(img);
        gridItem.appendChild(description);
        gridItem.appendChild(greeting);
        container.appendChild(gridItem);
    }
</script>

### Journey through Life

Here is what I did at those places

- Del Norte High School Pre-School (2014-2015)
- Monterery Ridge Elementary School (2016-2022)
- Oak Valley Middle School Years (2022-2025)
- Del Norte High School Freshman Year (2025)

### Culture, Family, and Fun

Everything for me, as for many others, revolves around family and friends.

- My mother told me that I was Filipino — here is my researched [family tree]({{site.baseurl}}/images/about/familytree.png)
- The gallery of pics has some of myself and my favorite food.

<comment>
Gallery of Pics — scroll to the right for more...
</comment>
<div class="image-gallery">
  <img src="{{site.baseurl}}/images/about/2025-12-01-084118.jpg" alt="Image 1">
  <img src="{{site.baseurl}}/images/about/fries.png" alt="Image 2">
</div>
