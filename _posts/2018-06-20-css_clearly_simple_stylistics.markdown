---
layout: post
title:      "CSS...Clearly Simple Stylistics...?"
date:       2018-06-20 13:10:28 -0400
permalink:  css_clearly_simple_stylistics
---


Cascading Style Sheets......seem pretty simple at first...Clearly Simple Stylistics maybe? So far so good, but I have feeling this may become more difficult in the coming weeks. More on that later...

For now, adding style to webpages is...well, pretty essential, no? It's great to have wonderful content that enthralls the reader during the exploration of a website...but what if plain content doesn't pull them in to begin with? That's where CSS comes in...adding various <font size="10">sizes,</font> colors, <b><u><i>stylings</i></u></b>, spacing, etc and so on and so on. Making a webpage visually attractive is much more effective than relying on awesome content alone. I haven't had a ton of experience with CSS yet, but I can't wait to explore more in future labs & projects to make some stunning sites!

And now nokogiri....is my new headache. Such a powerful Ruby gem for utilizing CSS tags for scraping info from sites. Off to explore this more and report back!

Annnnd....back! Nokogiri is awesome!...albeit a bit complex at first. Easy to install by running:

<background color="#eee">gem install nokogiri</background>

then enabling by adding this to the top of mycode:

<font color="#aaa">1  |  require 'nokogiri'
<p>2  |  require 'open-uri'</p></font>

The trick to understanding nokogiri is to really understand how to read CSS when using the Document Tools ("Inspect") for a webpage. It is sooo much easier to get a grasp of nokogiri once I was able to drill down into the CSS and pick up the specific tags that I wanted nokogiri to find to pull data from the page. I had to read more on CSS a few times to really get into it. Once I started understanding how to reference the different tags, i.e. id, class, div, p, etc, I was able to pull the specific tags I wanted in order to find the exact text, link, etc. I wanted from the webpage (i.e. .first, .text, .attribute, etc.) Understanding CSS made scraping webpages more clearly simple (...stylisitics?)
