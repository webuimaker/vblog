## Getting Started

(Assuming you know what Jekyll and Github pages are.)

* To start blog, simply git clone the repository on github.
* ```
git clone https://github.com/bisinis/village_blog.git 
```
* Install ```ruby``` and then do ```gem install jekyll```. 

* ```_config.yml``` describes all the variables which you are required to set. 



Things to change on `_config.yml`
====================
There is a config file at the root called `_config.yml`. By Default it looks like:
```
name: "Village Blog"
title: "Village Blog"
description: "Welcome to the Village Childcare Blog!"
logo: 'assets/images/Village2-01.png'
baseurl: 
google_analytics: 'UA-22916797-9'
disqus: 'demowebsite'
mailchimp-list: 'https://wowthemes.us11.list-manage.com/subscribe/post?u=8aeb20a530e124561927d3bd8&amp;id=8c3d2d214b'
include: ["_pages"]
permalink: /:title/
email: 'taylor@joinourvillage.com'

```


Things to change on `_post/.md`
====================
There is a .md files need to update as per the content. 

```
layout: post
title:  "title of post"
categories: cat name
tags: tag name
image: image path 
comments: false/true
author: author name
<!-- If you want to Gallery on post -->
gallery:   
- img: "image of path"
- img: "image of path"

<!-- After three '---' start write content  -->

```

```
{% include post-slider.html %}  for include gallery
```

FOr table 
===================

add ``` {:.table } ``` into table when you use table 


```
{:.table }
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```


if any issue to run then update  your environment to develop this, run ```bundle install```.


Use it!

```Jekyll server```

See the reult on browser 

http://127.0.0.1:4000


