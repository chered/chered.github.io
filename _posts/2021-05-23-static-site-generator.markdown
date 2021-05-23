---
layout: post
title:  "Static Site Generator for Simple Blog Website"
date:   2021-05-23 00:00:00 +0800
categories: CMS
image: /assets/images/jekyll-og.png
---
![Jekyll]({{page.image|relative_url}})

**KISS “keep it simple, stupid”**

Who would have thought that you can have a blog that will require no database. Yes you heard it right, a blog without database. 

Popular blog CMS like wordpress, drupal and joomla have been used widely through the years and it continues to do so. But over the years, loading speed test websites such as google pagespeed require these CMSs a need to have a lot of optimization to get a better speed score. And so static site generators emerge as an alternative solution for a these blog tools with quicker and leaner websites. 

Some of the most popular static site generators are [jekyll](https://jekyllrb.com/) and [hugo](https://gohugo.io/). This blog was built using jekyll.
## Advantages of Static Site Generators
### Simple
Static File Generators requires no database as all data are handled as a file. That means there is no way to hack using the traditional "SQL inject" on the database.  
### Speed
Because of no database, there is no query time in getting contents from database. All data are handled as file. File format is [Markdown](https://en.wikipedia.org/wiki/Markdown). 
### Version Control
100% totally file version control. No database means versioning is really on the file itself and we can use just github to do that. That means no need for a staging site to update and check everything including database update.  
### Portability
You want to move your static site generator website to a new host? Just "Copy and paste", as simple as that. 

If you require only a personal blog and you want to do it fast, Static File Generators might be the answer to that. It doesn't require a server like XAMPP or WAMP to develop  locally as it has it's own server built in.  

Although the features are still far from Wordpress, drupal or joomla, if you want only a simple personal blog with fast loading speed, Static Site Generator is an alternative choice.