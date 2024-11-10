---
layout: post
author: Douglas Krouth
title: "About this site"
categories: ["Projects"]
original_publish_date: 11-07-2024
---
**TL;DR**:<br>
* [Jekyll for serving and site generation](https://jekyllrb.com/)
* [GitHub Pages and Actions for hosting and deployment](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
* Raw HTML and CSS
* SquareSpace for domain ([R.I.P. Google Domains](https://domainnamewire.com/2023/12/26/top-stories-squarespace-buys-google-domains/))

***
## Motivation
I wanted to create a personal site that was simple and wasn't overly dependent on external libraries. This site is built with Jekyll and Liquid templates, served with GitHub Pages on a free-tier license. All HTML, Markdown and CSS is written in plain syntax (beyond templating) without tools like Tailwind, SCSS, etc.

My choice to avoid using external libraries was guided by two concerns:
1. **Keep the site's footprint reasonably light**<br><br>I am a fan of lightweight tools, websites, and documentation. To the disappointment of my friends and my family, I'm avid user of Vim (NeoVim), tmux, etc. and that's boosted my admiration of utilitarian design and display.<br><br>One of the guiding examples that I used for this site was Bjarne Stroustrup's personal site \[[link](https://www.stroustrup.com/)\]. It was built with the aim of providing access to as many users as possible and is served as pure HTML with small bits of inline CSS. I have a deep appreciation for minimalist websites, user interfaces, etc. and I used his website as inspiration for this site and other projects. 

2. **I am a chronic "adjuster" with personal projects** <br><br>An honest appraisal of one's shortcomings is critical to growth: I am fussy when it comes to modifying CSS and HTML elements. With larger tools like Tailwind and Bootstrap, I find myself going a bit overboard in terms of thinking about layouts, design ideas, etc. rather than just getting stuff done. From personal experience, I know that the more complicated this site becomes, the less I'd want to add content to it.

More examples of minimal static sites are listed below that I used for reference.
* [r/spartanweb](https://www.reddit.com/r/SpartanWeb/) (warning: reddit)
* [berkshirehathaway.com](https://www.berkshirehathaway.com/)
* [motherfuckingwebsite.com](https://motherfuckingwebsite.com/) (nsfw: language)
* [bettermotherfuckingwebsite.com](http://bettermotherfuckingwebsite.com/) (nsfw: language)

## Learning front-end design quickly : The Odin Project
The fastest, most budget friendly (it's free), and efficient way to learn front-end design is the Odin Project \[[link](https://www.theodinproject.com/)\]. The Odin Project site is structured into multiple "paths" which guide you through the foundational concepts of web design. Start with the *Foundations* path to learn HTML, CSS, and the Document Object Model (DOM). After completing the *Foundations* path, you're set to build a static site like this one.

For professional software developers and experienced programmers, you could complete the *Foundations* path in as little as a few days if you were mostly skimming and referencing the MDN documentation. If you have no experience in programming or prefer to take your time, expect to spend multiple weeks/months learning the material and going through the provided exercises, examples.

Other helpful resources that I used when working on this site:
* [Kevin Powell](https://www.youtube.com/kevinpowell) : Helpful and practical video tutorials on HTML and CSS. This channel is awesome.
* [Flexbox Froggy](https://flexboxfroggy.com/) and [Grid Garden](https://cssgridgarden.com/) : Fastest way to learn flexbox and grid fundamentals.

## Thank you to the Jekyll project
Jekyll provides a simple platform to build static sites without needing extensive knowledge of hosting, server-client interaction, or even programming (debatable). It abstracts all interactions with Ruby outside of a few small things like how to install a Gem and a few commands like *'jekyll serve'*.

Pages can be made as complex as you want, post content can be written in Markdown and formatted with CSS and templates. Allowing users to generate posts with Markdown is a productivity boon and enables folks with little experience in UI/front-end design to display content with minimal effort. If you can write a README, you can make a site with Jekyll.

