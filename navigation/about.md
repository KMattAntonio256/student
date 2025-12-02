---
layout: post
title: About
permalink: /about/
comments: true
---

## As a Conversation Starter

Here is where I live.

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

### Journey through School

Here is what I did at those places

- Del Norte High School Pre-School (2014-2015)
- Monterery Ridge Elementary School (2016-2022)
- Oak Valley Middle School Years (2022-2025)
- Del Norte High School Freshman Year (2025-Ongoing)

### Karate Achievements
- I have been to four tournaments across my Karate career. 
- I have placed in ever single one, my most prized being 1st place in weapons forms
- I have reached black belt after 7 years of hard-work and now intern at the dojo. Our form takes the longest to reach black-belt out of all fighting styles. 

### Experience
- I have started to coding before taking computer science. 
- I have ongoing projects in Roblox Studio where I have learned most concepts in the coding language lua. 
- I have learned how to do basically everything in Roblox Studio, build, code basic things and do planning for what I'm going to do next, or how I'm going to add more to the game.
- My partner Rohan has helped me out with building some of my games as well very helpful with some tasks that I don't have time to do. 


### Culture, Family, and Fun

Everything for me, as for many others, revolves around family and friends.

- My mother told me that I was Filipino and she moved with my dad here afor a fresh start away from the Phillippines. — here is my researched [family tree]({{site.baseurl}}/images/about/familytree.png)
- The gallery of pics has some of myself and my favorite food.

<comment>
Gallery of Pics — scroll to the right for more...
</comment>
<div class="image-gallery">
  <img src="{{site.baseurl}}/images/about/2025-12-01-084118.jpg" alt="Image 1">
  <img src="{{site.baseurl}}/images/about/fries.png" alt="Image 2">
  <img src="{{site.baseurl}}/images/about/Shrimp-Tempura-1.png" alt ="Image 3">
</div>
