---
published: true
layout: post
tags:
  - article
title: How I got this damn thing(website) working
hero: uploads/htmlshot.jpg
overlay: green
---
Here's how *solochro.me* works, for the curious.
{: .lead}

<!--break-->

- Hosting: Netlify + Github
  - Free. Automatic. Works. Wish I'd known Microsoft was acquiring Github though, because I would've used Gitlab instead. Might change over in the future, recommend that you start with Gitlab if you aren't tethered to Github already.
- Domain: Namecheap
  - True to the name, I got a really cheap domain for under $2, I think.
  - Make sure you choose a domain that can have proper privacy against WHOIS searches. I'd started out with a .us domain, which doesn't allow WHOIS protection. This means that anyone can look up who owns the domain, and get my name, address, etc. Could be avoided with an LLC or something like that, I suppose. Other TLDs come with some sort of optional WHOIS guard to hide your info.
- Email: Tutanota Premium
  - I pay to use my personal domain. 12 Euro for a year–but I'm having issues with fucking Namecheap and getting the MX records set up properly while having custom Netlify DNS. It's a bit of a headache, and I may end up transferring my domain elsewhere so I can have better management tools. That would cost a few extra bucks though. So for now I use a basic tutanota address as an alias. :woman_shrugging:
- Static Site Generator: Jekyll with 'Dactl' theme
  - I'd recommend [Hugo](gohugo.io) over Jekyll. It's leagues faster, and I will probably end up switching over to it at some point. There are great themes for Hugo as well, but this particular theme hasn't been ported over by anyone else...so I'd have to do it...and that's not a priority right now.
- CMS: Forestry.io or Prose.io, or nothing
  - They can be a little 'extra' for the simplicity of Jekyll or any other static site generator to be honest. All I have to do is set the proper YAML and filename format and commit my changes, and Netlify automatically pulls the changes from Github and generates the updated site.
  - I prefer Prose.io because Forestry doesn't really let you do shit the raw way, which is the point, but it can screw with the markdown and that's irritating.

- Photos: Unsplash or my own work + Photoshop abuse
  - I also use ImageOptim to scrub + er, optimize the images a bit.

{: .notice}
Photo by Ilya Pavlov on Unsplash.

At any rate, I made a few maybe suboptimal choices regarding my stack, but it's okay–one great thing about it is that everything is changeable. I'm no expert, but I did it on the cheap.
