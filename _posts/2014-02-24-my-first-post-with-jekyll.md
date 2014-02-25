---
layout: post
title: Welcome to my first blog post on Jekyll
excerpt: I've needed to sort out my blog for a long while. I'd had dreams of writing my own, in .NET and then ruby, but I never got around to it. Now I'm thinking why re-invent the wheel? So I was looking for a new solution.
---

I've needed to sort out my blog for a long while. I'd had dreams of writing my own, in .NET and then ruby, but I never got around to it. Now I'm thinking why
re-invent the wheel? So I was looking for a new solution. I had some criteria:

+ Free to host- Why would I want to pay if I can avoid it?
+ I can host on my own URL.
+ Quick - Like everyone else I want a nice and snappy blog.
+ Customisable - I'm a software professional. I like to play around a bit.
+ Not too difficult once you get into it.

Which led me on a little search across the internet. The ultimate conclusion of which was that I should give [Jekyll](http://jekyllrb.com/) a go and host the site on
[GitHub Pages](http://pages.github.com/). This fulfilled the ultimate requirement; its free. Now, how about hosting on your own domain? Yep,
 [GitHub Pages](http://pages.github.com/) let you do that as well. Bonus.
 
Speed is a very important issue. I've put things up on the free offering of [Heroku](https://www.heroku.com/), [Azure](http://http://www.windowsazure.com/) 
and [AppHarbour](https://appharbor.com/); they were all very slow for the free offering, with the real problem being startup time if the application fell 
asleep. So, why is [Jekyll](http://jekyllrb.com/) and [GitHub Pages](http://pages.github.com/) different. [Jekyll](http://jekyllrb.com/) is essentially a 
parsing engine that takes your your posts, written in [markdown](http://whatismarkdown.com/) for me and then converts them into a full static website. Complete with layouts
for code reuse. It's a bit like a push CMS. It runs as a ruby gem which creates the site which I then push to GitHub and its ready straight away. I'll give you some
useful links at the end of the post.

I've combined Jekyll with [Twitter Bootstrap](http://getbootstrap.com/) to give me a really nice and easy to style blog. I'm really happy with the result and I'll
continue to refine it for a while. Adding categories and tags, maybe add [disquss](http://disqus.com/) if it gets busy. I hope you like it.

Check out these links for some handy tutorials:

+ [Get started with GitHub Pages](http://pages.github.com/)
+ [The Jekyll tutorial](http://jekyllrb.com/docs/quickstart/)
+ [Markdown Syntax](https://daringfireball.net/projects/markdown/basics)


