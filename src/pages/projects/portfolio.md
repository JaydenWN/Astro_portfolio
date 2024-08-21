---
layout: ../../layouts/Project_Layout.astro
name: Portfolio
description: Web Developer Portfolio
created: 2024
image: /portfolio.png
url: /projects/portfolio
---
## Overview
I needed a central online location to showcase my web development experience and IT education. I aimed to create a website that is both accessible and scores high on lighthouse testing. The website also needed to be fully responsive.

## Technology
To create this portfolio website, the following technology was used:
-	Astro
-	Vanilla CSS
-	HTML Canvas
-	Markdown
-   tsParticles

## Features
-	Links to my professional social media accounts
-	Interactive HTML Canvas background
-	Ability to create HTML from markdown files
-	Showcase of my previous projects

## Challenges and Solutions
I aimed to create a blazing-fast website. To do this I opted to use Astro as it ships without JavaScript by default. I decided to use Astro without React as using React would be overkill for the task at hand. 

Astro also allows static site generation out of the box. This means I can create markdown files for my projects (what you are reading now), and have it converted into a static HTML page. 

I ran a lighthouse test on desktop and received a high score. This score could be improved with Astros built in Image component.


![Lighthouse score](/portfolio2.PNG)

One part of this project that I wish to improve upon is the design. With my not-so-great design skills in mind, I tried to ensure padding and spacing were used effectively. The design is also quite basic, however including the tsParticles background created with HTML Canvas seemed to help quite a bit.

## Final Remarks
Overall, I think I will opt to use Astro in future projects. I am particularly excited to use React within Astro and compare the performance of a single-page react application. 
