---
templateKey: blog-post
title: Free website - Built with Gatsby
date: 2020-06-24T18:04:10.000Z
featuredpost: true
featuredimage: /img/blog_1_gatsby.jpeg
description: A dream come true for a developer. My first blog post.
tags:
  - general
---

![Gatsby](/img/blog_1_gatsby.jpeg)

I always wanted to own a website for free. However I did end up paying for purchasing the domain from GoDaddy for 12\$. Otherwise,
most of this website is free.

This website is built for showcasing my current work that I am doing apart from routine job. Before dwelling into side project that I am currently working upon, I wanted to discuss about how I built this website for free.

## Gatsby

Let me come straight to the point, Gatsby is a **JAMstack** framework built using node, React. This **JAMstack** is like a new guy(tech) in the town.

## What is JAMstack

JAMstack stands for Javascript, API and Markdown. It is a serverless stack where the markdowns are statically served from the server directly. (Yes, we are back to the olden days where static pages are served directly from the server instead of them using browser to render the content). More info [here](https://jamstack.org/){target="\_blank"}

Well, I know that I threw a lot of technical terms above. Let me clear some of the doubts that may arise for you.

1. **Serverless** - You basically don't maintain any backend functionalities like authorization, database etc. Everything(most of the things) is maintained by your cloud provider or use any third party services to get a fully fledged website. All you got to do is to focus on writing your business logic. If you need more info , refer [this](https://www.netlify.com/blog/2018/08/06/five-key-benefits-of-going-serverless/){target="\_blank"}

2. **Statically served** - We use this term when the content is built on the server. When a request is made from the browser, content is built in the server and are rendered as whole in the browser. (Basically there is no client-side computation)

3. **Client Side Technologies** - There are technologies out there like for example Angular, React, VueJS, these all are the client side rendering technologies. Most of these technologies are used to build single page applications. They update the content dynamically by calling the APIs to server under the hood.

## How I built this website?

1. Well, it really simple and straight forward if you have any of the **GIT** accounts. If you do not have any git accounts I urge you to create a GIT account(Even if you are not a developer). Creating a GitHub account is easy and straight forward. [GitHub](https://github.com){target="\_blank"}.

2. Then go [this](https://github.com/netlify-templates/gatsby-starter-netlify-cms) url. Scroll down and click on **_Deploy to Netlify_** button

   ![netlify](/img/netlify_deploy.png){class="box message is_info"}

3. Then you will asked to authorize Netlify and click okay and then you are done! Yes that's it. Everything will be taken care of in the backend for you. A basic runnable site where you start posting blogs will be ready.

I know that you got all the website, but there is still a catch, you obviously have to customize yourself. To customize my website like adding analytics, changing domain name (with Let's Encrypt SSL certificate ), changing the welcome page and some cleaning-up, it took me around two days and that's it.

That's all for today. Signing off...
