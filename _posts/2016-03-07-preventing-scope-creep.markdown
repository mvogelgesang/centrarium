---
layout: post
title:  "Preventing Scope Creep"
date:   2016-03-07 21:45:00
author: Mark
categories: posts
tags:	scope creep, planning, lean
---

When creating Vogy Says, options for customization were endless. Do I make a wholesale change to the home page? How should posts be tagged and categorized? What about a logo for the site? Light blue is OK, but what about changing the color scheme? Fonts, perhaps some changes could be made there. What about a picture of myself, do I bother with that? Update the about page? What would I even write on it? What changes should be made to the posts template?

Coming up with ideas like the ones above are a natural part of the software development process. To a certain extent, these ideas can be helpful and lend towards the long term vision of a product. However, trying to address everything up front or getting bogged down in the details can inhibit early success. Instead, teams should start producing functionality and testing ideas- this is the basic principle of the _[Lean Startup](http://amzn.to/1puR9Y5)_ model shared by Eric Ries. For a blog, that means writing content. For an app that has a business goal, it means starting to address the underlying issue on piece of functionality at a time. 

Getting a product owner and the development team to adhere to this can be difficult. Both sides want to generate ideas, come up with slick new designs, and tackle problems in new ways. This is especially challenging if your scrum master or project manager does not provide thoughtful mediation between the two groups. At the end of the day, the role of the scrum master is to ensure functionality is delivered. Trying to be a good scrum master for my team of one, I wanted to ensure that I did not fall into this trap and instead focused on producing content. 

To get the site up and running, there were some updates to the ````_config.yml```` file that had to take place along with a handful of other files. In an effort to minimize those distractions before launch, I decided that I would spend no more than one evening updating the configuration of the site. While further customizing ````_config.yml```` or building out new sections would be great, they detract from the underlying goal. In an effort to ensure that I continue to write, I set some arbitrary benchmarks which should be achieved before new features can be built. It's as if writing content allows me to 'level up' and unlock new fatures. Each benchmark isn't tied to a specific feature but I'll work to prioritize the list as needed (currently it's not). I'll be updating this post as benchmarks are reached a features are deployed. 

## Benchmarks
* 5 posts
* 10 posts
* 25 posts
* 50 posts
* 100 posts
* 500 word article
* 1000 word article
* 2500 word article
* 5000 word article

## Features
* Update color of footer and headers
* Create a listing of blogs that I read including descriptions
* Connect CircleCI to repo for continuous testing and write article on it
* Update fonts for the site
* Migrate my former ice cream blog, [Prodigious Pint](http://prodigiouspint.blogspot.com), over to this blog
* Create custom layout for Prodigious Pint articles
* Create a plan for tagging/ categorizing content
* Create a slick 404 page
* Add tag listing to the bottom of each article
