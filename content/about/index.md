---
title: "About Me"
date: 2020-01-18T21:28:00-05:00
draft: false
hideLastModified: true
showInMenu: true
# no need for the "summary" parameter as it is not displayed in any previews
---

## Early Life

When I was 5 years old, my father bought a refurbished Apple Macintosh Plus and thus we became a "Mac family" for most of my childhood. I became endlessly fascinated with computers and especially video games; I played mostly Blizzard games (since they were the few AAA titles that were Mac-compatible), but I was jealous of other people who could play all those other games on "Windows." When I turned 12, I purchased a used Cyrix 100MHz system from my uncle and learned how to install Windows 95, upgraded the hardware (I quickly got rid of that garbage Cyrix for a Pentium 233 w/MMX!), and finally played some _real_ games! Later I bought a Dell XPS desktop for my 14th birthday, but after realizing I could've built my own PC with better specs for less money, I decided to never buy a retail desktop ever again. Over the past twenty years I've built dozens of PCs for family, friends, myself, and professionally.

My current PC is already a few years old now, but it suits my needs:
  * i5-6600K (lightly overclocked)
  * EVGA GeForce GTX 1060 3GB
  * 16GB RAM
  * Samsung 850 EVO 250GB SSD
  * Hitachi 1.5TB RAID1

I'll be building a new PC this year with my wife (she wants to learn) and we're going to use AMD for the CPU this go around. The new Ryzen chips look really cool!

## Education and Career

I originally went to college for Mechanical Engineering which I excelled in, but on a whim I took an Accounting course as an elective. I loved it so much that I decided to change my major. I completed an Associate's degree in Accounting in 2005 and my aspiration in my early twenties was to be a CFO someday. Not too long thereafter though I went through a pretty rough part of my life; I was working a crappy full-time job (with a long commute) while still going to school full-time, and I just couldn't keep up. I ended up dropping out of the University of Kansas in 2007 with only 40 credit hours left to graduate. Although I wanted to eventually finish, I bounced around for several years before catching a break: in January 2010, I got a job as a PC technician at The Ohio State University and my career has flourished ever since.

Since then I've gained exposure to nearly every part of IT operations, specializing in systems and network engineering. But that unfinished degree was always gnawing in the back of my mind.

In 2017, I made the decision to finish my degree, and I graduated _summa cum laude_ at Cleveland State University in May 2020 with a BBA in Management (and a minor in Accounting).

## Current Interests

These days I am most interested in cloud computing technology and software development, especially everything DevOps. I have played around in all three major cloud platforms, but most of my time has been spent in Azure and AWS. Kubernetes and Docker are quite fun to use and we've been evaluating potential use cases at work recently which is pretty cool. I recently completed my AWS Solutions Architect - Associate and I'm now studying for AZ-103 Azure Administrator and the CKA (Kubernetes). Additionally, I have been learning how to code, most recently working mostly with full-stack JavaScript (using MongoDB, ExpressJS, VanillaJS, NodeJS) and also using Python to automate some basic configuration tasks with Ansible and Vagrant.

## How This Website Was Built

I intend to eventually write a full blog detailing how I created this website, but for now, here is the basic overview. 

For various reasons, I didn't want to create a WordPress blog. Mainly I wanted to create something that was easier to manage. I discovered [Hugo](https://gohugo.io/) after dabbling with [Jekyll](https://jekyllrb.com/). I messed around with several different themes before settling on [ReFresh](https://themes.gohugo.io/hugo-refresh/). ReFresh is easily customizable, and I quite like the look and feel of it.

I use Git along with GitHub so that I can easily make changes whether I am at home or working from my laptop. The source files are a public [repo](https://github.com/grossmeyer/glennmeyer.dev) if you are curious how the website is put together.

CI/CD is handled by [CircleCI](https://circleci.com/) and is set to run on every GitHub change. After successfully passing a new build, CircleCI uses a webhook to notify [Netlify](https://www.netlify.com/) of the update, at which point Netlify will grab the latest files from GitHub. Netlify handles both the hosting and DNS. My domain name is registered with [Namecheap](https://www.namecheap.com/).

I use [VS Code](https://code.visualstudio.com/) for all of my editing as it makes working with Markdown files very straightforward.

[Chocolatey](https://chocolatey.org/) is a package manager for Windows that makes installing programs like Hugo a snap.

My avatar was created using the Google Chrome extension [Avatar Maker](https://chrome.google.com/webstore/detail/avatar-maker/ofknlbikfofijlcjkfcihomkedmchfbn?hl=en-US).

## Resources that helped me learn Hugo

I learned the basics by watching these videos by [Mike Dane](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3).

Picked up a few extra ideas from [Chris Stayte](https://www.youtube.com/watch?v=c7vpcqA6SEQ).

Netlify has a [nice tutorial](https://learn.netlify.com/en/basics/) on Hugo basics.

The [offical Hugo documentation](https://gohugo.io/documentation/) is great for going deep on how Hugo works.

Found random helpful stuff on the [Hugo Discourse Forums](https://discourse.gohugo.io/).

## Future Ideas for this website

It seems like a small thing, but I would like to match my \<a> tags to the green color scheme that I currently have customized. I've spent several hours crawling through the CSS for ReFresh, but haven't found a clean way to target just that. At this point I think it is somewhere in the SASS configuration, but I haven't learned much of SASS yet. If anyone knows how or where to change that, please let me know!

About the only thing I don't like about the ReFresh theme is that there isn't a simple way to navigate back to the homepage except hitting the back arrow or typing it manually. Ideally there would be a Home link in the top right that would take you back to the start. Not a big deal, but it bothers me. What that really means is that I will eventually rebuild this website completely customized from scratch. I'm already mulling that idea and am debating between using Django, Flask, or ReactJS. UPDATE: full update of this website is coming soon, written in JavaScript! Django and Flask are cool, but they aren't really what I'm looking for with the types of projects I have in mind, including my new website which will be more blog-like.

