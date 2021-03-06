---
layout: post
title: "Taking The Plunge: From Wordpress to Jekyll"
description: 
date: 2022-03-30 07:30:00
image: 
categories: [Webdev]
tags: [Webdev]
---
Hello Netizens! I wanted to make a small post explaining why I've decided to use Jekyll instead of Wordpress for my blog, despite it's features being much more limited in comparison, and talk about my experiences so far.

I used to run a WordPress blog on a self-hosted homelab server a few years ago with a bunch of other websites and video game servers (which started as a simple Raspberry Pi, then evolved into a Asus EeeBox EB1033, then a full-blown HP ProLiant G6 server), and as simple as it was to set up a WordPress blog with the magic of DietPi (a fantastic Ubuntu-based distro that gets a bunch of your favourite programs up and running in no time), I realized that maintaining a webserver can be...a bit of a time and money sink, to say the least. 

Between initially setting up my blog and now, I've moved houses over 3 times which has meant reconfiguring all of my servers every single time (with one unit I had moved into having such awful internet speeds that it wasn't worth using), I've been DDOS'ed to hell and back at random, and I've had to pay many a fee to maintain my old domain names (lain.app and accela.design). As my websites don't generate much traffic (or income lol), I decided to put having a static domain name on hold for now and move all of my static webpages from my server to GitHub instead, using FreeDNS to get subdomains for my pages.

Recently, I'd been reading about hosting static webpages on GitHub and decided to take the plunge and move a lot of my static websites over & convert my existing blog setup into a GitHub-friendly blog setup. Initially I was going to write a static index page and go through the extremely exhausting process of updating it every time I made a new post, and linking to the new post as an .html file somewhere, but after some research I learned about Jekyll and decided that was a much easier and much less painful route to go down. Getting started with Jekyll was incredibly easy thanks to the Chirpy theme by cotes2020. All I had to do was fork their quickstart page, edit the _config.yml file with information relating to my blog, and give it a few minutes to generate the blog before going to the GitHub Pages settings and setting the shared page to the "gh-pages" branch & changing my CNAME to my subdomain from FreeDNS. After a few more minutes everything was working perfectly, and now I have a safe place to run a blog without fear of downtime, DDOSes or catastrophic data loss!

There are a few caveats to using Jekyll in comparison to Wordpress (ie; less features and plugins, having to learn a new posting format, etc.) but I find what Jekyll has to offer is perfect for what I need as a small-time tech blogger. 

Anyway, that's all I really wanted to talk about on the matter as I still need to get more familiar with the blogging platform, but thank you so much for reading! Take care and stay safe! 

- Faith Void
