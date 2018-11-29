---
layout: post
title:  "On Jekyll, Github, and Developing... as a Designer"
date: 2017-05-05
excerpt_separator: <!--more-->
published: true
---

![Atom Editor: What I stared at for 3 weeks](/assets/img/blog-img/jekyll-git-dev.png)

 It's been a while in the making, but it is here, and it is _glorious_. As you may well know, launching a new site is an arduous, yet rewarding task; so please indulge me by cracking open a bottle of your favourite tipple, and read all about what took so long.

<!--more-->

***

The previous incarnations of this site focused more around what I could actually do with my CMS of the time, WordPress. Rather than thinking about what I wanted to create, I spent far to much of my time worrying whether or not I had the technical skills to actually deliver it. Even though I managed to create a half-decent WordPress theme, I really didn't have any buy-in to maintain it, as I was petrified of breaking it when the next update popped up (which has happened more times than you'd realise). This time around, I've scrapped WordPress. After a brief dalliance with [SiteLeaf CMS](https://www.siteleaf.com), I settled with the static site generator [Jekyll](https://jekyllrb.com) due to its speed, flexibility and (relatively) easy-to-use templating language, Liquid.

Once upon a time this beautiful little slither of cyberspace was wholly devoted to blogging on design topics. From there, it expanded to include other topics grouped under the same theme: typography, branding, service design, and design thinking; and then further afield to things like architecture and interior design. That main focus is something I want to bring back, as it was that something that I enjoyed both on a personal and a professional level. Articulating ideas is tough, and only practice is going to make it better, so why not take the dive and start all over again?

With this goal in mind, I couldn't bring myself to use only Medium or Twitter as a platform - I felt it would be a bit impersonal. I expect to duplicate posts to those channels in time, but for now all posts will live here on this beautiful blog.

## Process

I resolved that the only way I'd be able to get this thing up and running in the timeframe I wanted, was if I treated it like a client project in three weekly sprints. Each week I identified what I wanted to achieve, and then didn't stop until I finished that particular set of requirements. My requirements list was pretty simple:

- HTML & CSS only, no databases
- Easy to use, Markdown-friendly blog
- Fairly complex case studies, with a link to live sites
- Little to no javascript, aside from typekit and GA code snippets (this can come later with more complexity)

I chose to focus more on pages than on functionality, as I'd be thinking of specific functionality if I required it. Would I need a contact form? Nope. (More on that at a later date). Would I want a fancy pants social wall? Again, no. So the only real functionality I had to deal with was creating the media queries to make the site responsive.

Then there was the question of where to host it. I toyed with the idea of hosting on Github Pages mainly because of their CDN, not, as I found out later, because of the integration with Jekyll. However this would involve learning Git, which would slow the process further. I left the site on my own server, and vowed to return to Git and learn it another time.

Now I had my direction, my pages, my functionality scoping, and my timeframe. So far, so good.

## Build

I started the design of the site midway through 2016, and innumerable drafts of a homepage PSD later, I realised that nothing would really _work_ until I sat down and started to code everything up on screen. This isn't how I normally work. Normally I'd pore over technical documents and data outputs, peruse personas and meticulously plan and design every interaction. Not so with this. I wanted this site done, up and running, warts and all. What happened next was simple: I smashed out a load of templates from scratch - the only framework I used was [normalize.css](https://necolas.github.io/normalize.css/), the rest was a ground up, super simple site that would do what I wanted and nothing else.

I found that for someone who hasn't really touched code for 3-4 years this was phenomenally fun and challenging in equal measures, and I got a real buzz out of actually creating something which didn't suck. I've promised myself go back and add in little javascript features, again built from the ground up, once I've learned the basics.

## Content

For a change, I wrote the case studies first in Markdown in a very loose format. From there, I managed to code up a template which I thought worked quite well, and allowed me to say everything I wanted in a concise, structured manner. I can't say that I was too surprised that this worked well - after all, "content is king" - and having a set of text documents to work from helped separate concerns right at the start of the project. It also helped me plan the page structures and hierarchies, which hopefully any UI designer can relate to.

Images proved more troublesome that I anticipated. I wanted quality, but I also wanted reasonable file sizes - something which I found to be a balancing act which I couldn't win. Let's just say I'm working on this one with a few developer friends of mine in future.

## Bringing it together

> "Laugh at perfection. It's boring and keeps you from being done." - [The Done Manifesto](http://www.manifestoproject.it/bre-pettis-and-kio-stark/)

I struggle with the concept of 'done'. I can't stop myself from wanting to continually fiddle, change and edit things. Which is why it was so important to impose a deadline on myself, otherwise nothing would ever get truly 'done'.

After weeks of solid work, I finally have a portfolio I'm proud of. It _will_ change slightly from time to time, and there will be plenty to talk about, but in essence, it's done. I'm going to keep plugging away and add more content and work as time goes by - and possibly a store - so stay tuned, and come back often. Please.

***

There you have it! That's my experience of creating a whole static site from scratch. I hope you like what I've created here, and please let me know if you spot anything that shouldn't be there. Adios for now!

Jake.
