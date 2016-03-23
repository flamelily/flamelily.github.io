---
layout: blog-page
img: /img/blog/jekyll-logo.png
link: https://jekyllrb.com
caption: Jekyll simple, blog aware static sites 
category: Development
tags: jekyll,github,static,development,blog
permalink: /:year/:month/:title/
title: Moving to Jekyll and Github pages
description: |
excerpt_separator: <!--more-->
---

We have just migrated our website to Github pages which uses the excellent static site generator Jekyll.<!--more--> Static site generators have been around for a bit now and we moved our site and blog to enable an enhanced browsing experience for users. Our site is now very fast and we have shaved seconds off the loading time, as our old WordPress site used a MYSQL database which always adds to the overhead. Since we last looked at Jekyll and Github pages a few years ago, Github have made some [excellent improvements](https://github.com/blog/1715-faster-more-awesome-github-pages){:target="_blank"}. Pages now use a global CDN (Content delivery network) to serve local versions of your HTML content.<a href="https://pages.github.com/"><img class="img-responsive center-block" target="_blank" src="/img/blog/jekyll.jpg" alt="Jekyll and Github"></a>
Github also now mitigates DOS (Denial of service) attacks to your pages in the same way it protects Gitub itself. Since hosting on Github pages is free, this can be a great solution for small businesses wanting a fast responsive website with the ability to update it using the simple editing tools on Github. You can create posts for blogs using the simple [Markdown format](https://daringfireball.net/projects/markdown/){:target="_blank"} and upload them to Github for immediate publish.

See our web page speed test below to see the improvements this change has made.
<a href="http://www.webpagetest.org/"><img class="img-responsive center-block" target="_blank" src="/img/blog/webpagetest.png" alt="Web page speed test"></a>
Jekyll runs on Ruby and you don't need to use Github to setup and test Jekyll on your own machine. Follow the setup instructions on the main Jekyll page and give it a go. Just click the image below to see how to install Jekyll yourself, but be aware it's quite easy if you are using a unix based setup like a Mac or Linux, but a little more difficult to get [setup on Windows](https://jekyllrb.com/docs/windows/){:target="_blank"}.
