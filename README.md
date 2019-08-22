# DevConZm Blog

[![Netlify Status](https://api.netlify.com/api/v1/badges/9abde3fa-0bb3-4657-81d4-8a2629d95c2b/deploy-status)](https://app.netlify.com/sites/blog-devcon/deploys)

> A blog for [DevCon Zambia](https://devcon.co.zm) 

## Development

Run `gridsome develop` to start a local development server, or `gridsome build` to build the static site into the `dist` folder.

See the [Gridsome docs](https://gridsome.org/docs) for more information.

or reference [this guide]() to get an overview of how to contribute to this project.

# Creating a New Post 

Go to the content folder and make a new markdown file - `.md`
Be sure to start the post with this
```yaml
---
title: "Post title" # required
slug: post-title-custom-url # optional, override the auto-generated post slug
description: "Lorem ipsum description sit amet" # required, used in meta tags and RSS feed
date: 2019-03-01 17:54:43 # required; time is optional, but recommended for the <time> tag and better post sorting control
author: bleda # optional
tags: ['markdown', 'design'] # optional
cover: https://example.com/path/to/cover/image.jpg # optional parallax post cover image
fullscreen: false # optional - when `true`, makes parallax cover image take up full viewport height
excerpt: "Custom excerpt to show in archive pages" # optional
---
```