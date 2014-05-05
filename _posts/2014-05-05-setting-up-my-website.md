---
layout: post
title: "Setting up my website"
modified: 2014-05-05 15:37:13 +0530
category: tech
tags: []
image:
  feature: 
  credit: 
  creditlink: 
comments: true
share: 
---

I was looking for a suitable domain name provider for my personal website and I decided to go with <a href="https://www.namecheap.com/">namecheap</a>. After successfully setting up my domain, I wanted to design my website and my primary goals were to keep it simple, elegant and maintainable. With some googling, I found <a href="https://github.com/jekyll/jekyll">Jekyll</a> to be appealing and started reading its documentation and it took me almost three nights to set it up. I always tend to read the documentation thoroughly before starting on anything new, personally this works for me. 

<h2> What is Jekyll, exactly? </h2>
Jekyll is a simple, blog-aware, static site generator. It takes a template directory containing raw text files in various formats, runs it through <a href="http://daringfireball.net/projects/markdown/">Markdown</a> (or <a href="http://textile.sitemonks.com/">Textile</a>) and <a href="http://wiki.shopify.com/Liquid">Liquid converters</a>, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server. Jekyll also happens to be the engine behind <a href="http://pages.github.com/">GitHub Pages</a>, which means you can use Jekyll to host your project’s page, blog, or website from GitHub’s servers for free.

<h2>Setting up Jekyll on Linux:</h2>
You can follow this <a href="http://jekyllrb.com/docs/quickstart/">guide</a> to setup Jekyll on a Linux box. You can find more about Jekyll in this <a href="https://github.com/jekyll/jekyll/wiki">wiki</a>.
For a quick bootstrap on how to use Jekyll to set up blog, follow <a href="http://jekyllbootstrap.com">Jekyll Bootstrap</a>. This also provides information on Themes and other hacks to play with.

<h2>Comment Engine</h2>
I used Disqus to power my comment section and setting up it in one’s blog is very simple and on a Jekyll powered site it’s bliss. You can follow the below steps to integrate disqus into Jekyll site:
<ul>
	<li>Add a variable called <code>comments</code> to the <a href="https://github.com/mojombo/jekyll/wiki/YAML-Front-Matter">YAML Front Matter</a> and set its value to <code>true</code>.</li>
 	<li>In between a <code>% if page.comments %</code> and a <code>% endif %</code> tag, add the <a href="disqus.com/admin/universalcode/">Universal Embed Code</a> in the appropriate template where you'd like Disqus to load.</li>
 </ul>

You can find more information about Disqus comments <a href="http://help.disqus.com">here</a>. 

<h2>Source Code</h2>
What better way is there to host the source code other than <a href="https://github.com">Github</a>? You can clone my <a href="https://github.com/aravind646/aravind646.github.com">repository</a>.