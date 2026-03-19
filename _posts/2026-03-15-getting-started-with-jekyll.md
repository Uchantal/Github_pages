---
layout: default
title: "Getting Started with Jekyll and GitHub Pages"
date: 2026-03-15 10:00:00 +0000
categories: [jekyll, github-pages]
---

# Getting Started with Jekyll and GitHub Pages

If you've ever wanted to create a personal website or blog without paying for hosting, Jekyll and GitHub Pages are an excellent combination. In this post, I'll walk you through the basics.

## What is Jekyll?

Jekyll is a static site generator written in Ruby. It takes your content (written in Markdown), runs it through templates, and produces a complete static website ready to be served.

## What is GitHub Pages?

GitHub Pages is a free hosting service offered by GitHub. It integrates directly with your GitHub repositories and can automatically build and deploy a Jekyll site every time you push changes.

## Why Use Them Together?

- **Free hosting** — No monthly costs
- **Version control** — Your website code lives in a Git repository
- **Simple workflow** — Write in Markdown, push to GitHub, site updates automatically
- **Custom domains** — You can use your own domain name

## Setting Up

1. Create a GitHub repository named `username.github.io`
2. Install Jekyll: `gem install jekyll bundler`
3. Scaffold a new site: `jekyll new my-site`
4. Add the `github-pages` gem to your Gemfile
5. Push to GitHub and enable GitHub Pages in repository settings

## Final Thoughts

Jekyll and GitHub Pages make it incredibly easy to maintain a personal website. Once set up, all you need to do is write Markdown files and push — your site handles the rest!
