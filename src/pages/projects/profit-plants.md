---
layout: ../../layouts/Project_Layout.astro
name: Profit Plants
description: A Shopify Store Application
created: 2024
image: /profitplants.PNG
url: /projects/profit-plants

---
## Overview
Profit Plants is a Shopify application that introduces an eco-friendly gamification experience within an e-commerce Shopify store. The application grants customers the opportunity to plant a tree within a store's virtual forest once they make a purchase.

I developed this Shopify application during a break in between trimesters while I was studying at Torrens University Australia. I recently completed a group report assessment, which revealed that customers tend to purchase more when products are eco-friendly. Additionally, the assessment showed that gamification leads to an increase in overall revenue. The foundational idea of the Profit Plants application was driven by these findings.

## Technology
Web development technology used to create the Profit Plants Shopify application include:
-	Remix
-	Prisma ORM
-	Shopify Polaris
-	Shopify Liquid
-	Shopify Admin REST API
-	HTML Canvas API
-	Pixilart
-	Cloud Deployment

## Features
Features of the Profit Plant Shopify application include:
-	Ability to create a virtual forest within a Shopify e-commerce store
-	Ability to customize the forest
-	Paying customers can plant a virtual sapling
-	The sapling will grow into a tree in 24 hours, enticing customers to re-visit the store.

![Customize your profit plants forest](/profitplants2.PNG)

## Challenges and Solutions
I had previous experience in using Remix, Prisma and REST API’s. However, Shopify has a few rules and guidelines for the styling of the admin side of the application. Shopify Polaris helped in abiding by these styling rules, but it required me to follow additional documentation.

This project was the first time I had to use Shopify’s templating language, Liquid. I was able to pick up the concept quite quickly, as I have previously worked with other templating languages such as JSX.

As the project's main goal was to create a game, I had to find a solution. To do this I decided to use an HTML canvas. This allowed me to inject an HTML canvas inside a Shopify App Block. Before this project, I did not know how the canvas API worked or even how framerate worked within a game. I now use the knowledge gained on Canvas from this project and include it in my other web development works, such as the background of this portfolio website.

Profit Plants also needs to be run on a server, as it is a Remix application. For deployment, I opted to use Digital Oceans, App Platform. I decided to use Digital Ocean over AWS as I find Digital Ocean’s deployment quite frictionless.

Finally, I am not the greatest graphic designer, but Profit Plants requires game assets. Following inspiration from the game Stardew Valley, I decided to go with a pixel art design. All assets that are used within Profit Plants were created on the Pixilart SaaS website.

![Profit Plants Pixel Art Icon](/profitplants3.webp)

## Final Thoughts
Overall, this project strengthened my knowledge of the Remix frontend framework, granted me in-depth knowledge of the Canvas API and allowed me to grow my experience with deploying web applications on cloud infrastructure. Additionally, the project familiarized me with adhering to styling rules and guidelines, resulting in a successful launch on the Shopify App Store.
