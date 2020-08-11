---
title: "Contribute"
date: 2020-08-11T09:19:29+11:00
slug: "contribute"
description: "How do I contribute to this site?"
keywords: ["administration", "contribution"]
draft: false
tags: ["admin"]
---

## Introduction
Hi, this is a site managed by [Ethan Longe](https://github.com/ethanlonge) if you are in need of assistance in editing this site feel free to email him at ethan.longe@gmail.com

## Technologies built on
This site is built using Hugo on the Codex theme. This means all the content is written in Markdown. If you do not know what markdown is, this is a great guide to get started: [https://www.markdownguide.org](https://www.markdownguide.org). 

## GitHub
Once you understand how you edit the site, you can then create a branch on our [GitHub Repo](https://github.com/ethanlonge/math1007-site) and then make your changes and make a pull request. There are many good tutorials on how to do this. Once our team of moderators has accepted your changes, we will then push it to the master branch which will then update the site. Please make sure to also put your name in the author section on any pages you create so people can see what you have written

## Creating a new page
If you want to create a new page, just copy and paste a different page and change the content (change the tags to reflect the unit you are writing for). Please place it in the ```/blog``` folder. Name it as ```{unit}_{name}``` and when you are done with it, commit and open a pull request

## Date Part
If you need help with the date part, this should be the right date (refreshing should update it): \
<span id="contribute_date_now"></span>
<script>document.getElementById("contribute_date_now").innerText = new Date().toISOString();</script>