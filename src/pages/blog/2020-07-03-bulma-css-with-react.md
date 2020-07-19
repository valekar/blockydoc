---
templateKey: blog-post
title: How to setup Bulma CSS with React
date: 2020-07-03T18:04:10.000Z
featuredimage: /img/bulma-banner.png
featuredpost: false
description: How to setup Bulma CSS framework with React.
tags:
  - React
---

![Bulma](/img/bulma-banner.png)

Today I wanted to build a single page application with React today. And so, I wanted to set it up as quickly as possible. Of course, as you might already know that we need a **good CSS Framework** to make a website beautiful and most importantly responsive.

My usual choice would be to use **Bootstrap 4**. However, recently I came across **Bulma** and I wanted to try it out. And to be honest, the learning curve is so small that you can instantly create a great enterprise kind of application with it. And I am loving it.

## What is Bulma

[Bulma](https://bulma.io/){target="\_blank"} is simple CSS framework built using [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox){target="\_blank"}. It has over 40k plus stars on github and many developers love it because of it simplicity.

## How to setup Bulma CSS framework with React.

After searching through the internet, I couldn't find a proper way to setup React with Bulma CSS and finally after combining a few notes from different websites, I was able to figure it out.

1.  Create your react with

    ```
    npx create-react-app example
    cd example

    ```

2.  Install Bulma and sass related modules.

    ```
    npm i bulma
    npm i node-sass

    ```

3.  Change `index.css` to `index.scss` and add the below import

    ```
    @import "bulma/bulma";

    ```

4.  Since you have changed the file name from `index.css` to `index.scss` be mindful of changing the import in `index.js` file as well

5.  And after running the `yarn start` or `npm start`, you should be able to use Bulma CSS.

<br/>

#### TADA!

![bulma_localhost](/img/bulma_localhost.png){class="box message is_info"}

**PS** : I have added some html code to show you navbar and header in the above page. For more details visit [Bulma.io](https://bulma.io/documentation/layout/hero/){target="\_blank"}.
