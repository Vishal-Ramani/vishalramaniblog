---
id: 001
title: 'How to setup a blog using GitHub Pages?'
date: 2023-01-20 09:01:00 +0100
categories: [Blog, GitHub Pages]
tags: [blog, github pages, jekyll]     # TAG names should always be lowercase
author: 'Vishal Ramani'
layout: post
guid: '001'
permalink: /article/setup-blog/
custom_permalink:
    - article/setup-blog/
---

## Setting up GitHub repository.
* Create a GitHub account if you don't already have one.

* Go to the GitHub Pages website (https://pages.github.com/) and click on the "Start building" button.

* Choose a repository name for your blog, such as "vishalramaniblog" and select "Create repository."

* In the repository, click on the "Settings" tab.

* Scroll down to the "GitHub Pages" section and select the "master" branch as the source for your GitHub Pages site.

* Click on "Save" to enable GitHub Pages for your repository.

* Create a new file called "index.html" in the repository. This file will be the home page for your blog.

* Use HTML and CSS to design the layout and style of your blog. You can also use a pre-made theme or template if you prefer.

* Once you have finished designing your blog, commit the changes and push them to the "master" branch.

* Your blog should now be live at the URL[https://vishal-ramani.github.io/vishalramaniblog/] provided by GitHub Pages in the settings section of your repository.

* To continue adding new blog posts, create new files in the repository, and then commit and push the changes. Your new posts will automatically be added to your blog.

## Setting up custom domain for GitHub pages.

* Purchase a domain name from a domain registrar such as GoDaddy, Namecheap, or Google Domains.

* Log in to your GitHub account and go to the repository for your GitHub Pages site.

* Click on the "Settings" tab.

* Scroll down to the "GitHub Pages" section and click on the "Custom domain" option.

* Enter your custom domain name (e.g. vishalramani.in) in the "Custom domain" field and click on "Save".

* Go to your domain registrar and navigate to the DNS settings for your domain.

* Create a new "A" record for your domain that points to the IP address of GitHub Pages, which is 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153.

* Create a new "CNAME" record for your domain that points to your GitHub Pages username.github.io. (e.g. vishal-ramani.github.io)

* Wait for the DNS changes to propagate. It can take anywhere from a few minutes to a day for the changes to take effect.

* Once the DNS changes have propagated, you should be able to access your GitHub Pages site via your custom domain.

* You also can add a "www" version of your domain by adding a new CNAME record that points to your custom domain name (e.g. www.vishalramani.in)

Note: If you are using a subdomain for your GitHub Pages, you need to create a new "CNAME" record for the subdomain that points to your GitHub Pages username.github.io. (e.g. blog.mywebsite.com)






