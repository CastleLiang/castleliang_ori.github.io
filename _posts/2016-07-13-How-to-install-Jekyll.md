---
layout: post
section-type: post
title: How to install Jekyll
category: Web
tags: [ 'jekyll', 'ruby']
---


***What is Jekyll***  
If you want to build a static website without databases, comment moderation and updating, it is very convenient for you to use Jekyll, which can transform your plain text into static websites and blogs.
  
> Namely, Jekyll is a simple, blog-aware, static site generator, which takes a template directory containing raw text files in various formats, runs it through a converter (like Markdown) and our Liquid renderer, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server. 
<br/>
<br/>

***Requirement***  
There are a few requirements you'll need to make sure your system has before you start installing.
- Ruby
- RubyGems
- NodeJS
- Python 2.7
<br/>
<br/>

  
***How to install Jekyll***  
You can follow [installation doc](https://jekyllrb.com/docs/installation/)  
There are some following problems I have handled:
1. Don't use command as "gem install jekyll --pre" to install jekyll, because the pre-release version may cause the local server interrupt. Just use "gem install jekyll"
2. About port 4000: the Jekyll defaultly use the port 4000 to build the localhost:4000. So if you open some applications like Foxit reader which could occupy the port 4000, you will face an error in command "Jekyll serve".
3. Remember to install preliminary component before use your theme: For example, I haven't installed jekyll-per... So I faced an error. You can use a command like "gem install jekyll-per..." to install the pre-component.
<br/>
<br/>

***Advice***  
It is great to use GitHub pages and Jekyll to build a blog-website like this. And using git bash to input command is also a good choice. We all love git :heart_eyes:
<br/>
<br/>

