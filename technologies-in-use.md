---
heading: ''
sub_heading: Engineering and Health Sciences
layout: home
title: Technology in use
banner_image: ''
hero_button:
  text: ''
  href: ''
textline: ''
services: []
show_news: false
partners: []
show_staff: false

---

Google sheets, Strapi API, static sites via git, Vercel, Netlify

# Content Management

* [Forestry docs](https://forestry.io/docs/welcome/)
* [Jekyll Developer Guide](https://forestry.io/docs/guides/developing-with-jekyll/)
* [Jekyll docs](https://jekyllrb.com)
* [Hugo Developer Tools](https://gohugo.io/tools/ "Hugo Developer Tools")
* [Hugo docs](https://gohugo.io/documentation/ "Hugo docs")
  * Strapi
  * Netlify
  * Vercel
  * Nodegoat
  * Google Sheets
  * BigMl
  * R-Studio
  * Postgresql
  * Digital Oceean
  * Heroku

This website is managed via [Forestry CMS](https://forestry.io), which updates markdown files in [Github](https://github.com/biomassives/ecwo "biomassives github account - 'personal account'"), triggering a build at [Netlify.com](https://netlify.com "Netlify")

Forestry.io provides a solid interface to manage public content.

[scdhub.org](https://scdhub.org "SCD Hub") [solutions library](https://scdhub.org "Solutions Library") content is managed via metadata,  The transition to forestry.io free and now low level service has gone well.  SCD Hub is currently maintained via markdown files at https://scdhub.org 

The template we use for this website has been pre-configured to work with Forestry, 

 SCD Hub is using a hugo template, which indexes content by tags and categories, with the following endpoints:

 

"just import your repository ✨.  
Any changes you make will be commited back to the repo, and deployed if you're using Netlify."

<p><a href="[https://app.forestry.io/quick-start?repo=forestryio-templates/belkirk-jekyll-demo&engine=jekyll](https://app.forestry.io/quick-start?repo=forestryio-templates/belkirk-jekyll-demo&engine=jekyll "https://app.forestry.io/quick-start?repo=forestryio-templates/belkirk-jekyll-demo&engine=jekyll")"> <img alt="Import this project into Forestry" src="[https://assets.forestry.io/import-to-forestryK.svg](https://assets.forestry.io/import-to-forestryK.svg "https://assets.forestry.io/import-to-forestryK.svg")" /> </a></p>

Forestry empowers editors with a usable interface to edit Markdown, YAML and JSON files:

![](https://res.cloudinary.com/forestry-demo/image/fetch/c_limit,dpr_auto,f_auto,q_80,w_1205/https://forestry.io/uploads/2018/12/draft-post-editor.png)

* 

## Deployment

The easiest way to deploy this Jekyll v4 demo is to build and deploy through [https://netlify.com,](https://netlify.com, "https://netlify.com,") just click the button below and follow the instructions.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/forestryio-templates/belkirk-jekyll-demo)

## Running locally

### Requirements

* Ruby > 2.4
* Bundler > 2.0
* Jekyll > 4.0

Once you've cloned the repository:

    # Install project dependencies
    bundle install
    
    # Run a local server to preview your work 
    bundle exec jekyll serve