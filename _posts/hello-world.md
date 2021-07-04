---
title: 'How is this site built'
excerpt: 'Yes, I am victim of one blog engine per blog post syndrome, well known among programmers. Here is how this blog was built.'
coverImage: 'https://www.coywolf.news/wp-content/uploads/2021/04/og-ipfs.png'
date: '2021-06-04T05:35:07.322Z'
author:
  name: Adam Sobotka
  picture: '/assets/blog/authors/adam.jpeg'
ogImage:
  url: '/assets/blog/hello-world/cover.jpg'
---

Yes, I am victim of one blog engine per blog post syndrome, well known among programmers. Here is how this blog was built.

## Next.js

A big part of what you see is a sample code from Next.js - a framework built on top of React. Next provides a several advantages over React - most of them not visible on a statically generated site. When my friends asks for recommendation for this use case, I usually recommend 11ty. But I am too comfortable with Next, I know this code from other projects and it is easy to customize the outcome. It also makes using markdown files very easy.

## Tailwind

Tailwind is a utility library for styling (CSS). While most of professionals dismiss the usefulness of this tool, I love it. It makes a stylesheet syntax logical and easy to use. In my, flame starting opinion, Tailwind is what CSS should have been from start.

## Fleek

Fleek allows you to host your Next (and other frameworks) on IPFS. Which is not an easy job. IPFS allows for hosting only static files, in a same way as a Github pages. So what Fleek needs to do is to build the whole site, export it to the static files and host it on the IPFS. IPFS is a short of Interplanetary File System, a new way of distributing files over the internet.
