---
templateKey: blog-post
title: DraftJS with React
date: 2020-07-20T00:04:10.000Z
featuredimage: /img/draftJS.png
featuredpost: false
description: How to steup draftJS editor with React.
tags:
  - React
  - DraftJS
---

![DraftJS](/img/draftJS.png){class="has-text-centered"}

Lately, I have been working on adding a **wysiwyg** kind of editor in my react app. I came across many editors. So while googling I came across a few editors. A few of them can be found [here](https://blog.hubspot.com/website/best-wysiwyg-html-editor){target="\_blank"}. However I specifically wanted to add one that is suited for react applications. Thus I discovered another editor. Enter **DraftJS**.

**[DraftJS](https://draftjs.org/){target="\_blank"}** is specifically built for ReactJS. So, I started to play around. However, setting it up was not straight forward. I encountered a slight difficulty while trying to properly setup in a react app. But, this difficulty didn't stop me from setting it up and using it.

## How to setup DraftJS ?

So, how do we setup DraftJS easily?. So my quest began on how to set it up easily. Once again, after a few searches I came across this **[video](https://www.youtube.com/watch?v=XGxdCXyMC7k){target="\_blank"}**. Other videos didn't help me much. But let me quickly summarize you on how to set it up.

## Steps to setup DraftJS in React.

After searching through the internet, I couldn't find a proper way to setup React with Bulma CSS and finally after combining a few notes from different websites, I was able to figure it out.

1. In your react app, create a new component. Say for instance **example.jsx**

2. Now create a new css file in the same level as your newly created component. For example create **Editor.css** file.

3. Go to this [URL](https://github.com/facebook/draft-js/tree/master/examples/draft-0-10-0/rich){target="\_blank"} and copy the content of **RichEditor.css** file and paste it in **Editor.css** file.

4. Import **Editor.css** file in your **example.jsx** component.

5. Also import **Draft.css** file in your **example.jsx** component. This is **super** important. Otherwise, it doesn't work.

6. So, after importing CSS, your example.jsx import should look something like this

   ```
   import React from "react";
   import "draft-js/dist/Draft.css";
   import "./Editor.css";

   ```

7. After that go to this [URL](https://github.com/facebook/draft-js/blob/master/examples/draft-0-10-0/rich/rich.html){target="\_blank"} and copy only the class content in this html file to your **example.jsx** component. ( I will not add the code below to keep the steps simple)

8. Now run npm start and voila, you should be able to see something like this.

   ![DraftJS-setup](/img/draftjs-setup.png){class="box message is_info"}

**PS : If you are unable to setup properly, please follow this [video](https://www.youtube.com/watch?v=XGxdCXyMC7k){target="\_blank"}**
