---
layout: default
title: Introduction
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

## Introduction

Hello there! This documentation will help you use Notion to the fullest. The goal of this document is to provide a complete walkthrough that will make you a pro Notion users at the end. We will also provide small tips and tricks to optimize your workflow when you are using Notion.

### Intended Users

This documentation is targeted towards the following users:

A student in need of good way of organizing notes and tasks.

### Prerequisite Knowledge

1. Users will be required to know how to install an app on their device.
2. Users are expected to konw what operating system they are using. 

### Software Requirements
1. Users are are required to have Windos or Mac OS as their operating system
2. Enough storage, ram and internet connection is required for installation and syncing.

### Procedures Overview

1. Install the Ruby Gem
  ```bash
  $ gem install just-the-docs
  ```
  ```yaml
  # .. or add it to your your Jekyll site’s Gemfile
  gem "just-the-docs"
  ```

2. Add Just the Docs to your Jekyll site’s `_config.yml`
  ```yaml
  theme: "just-the-docs"
  ```

3. _Optional:_ Initialize search data (creates `search-data.json`)
  ```bash
  $ bundle exec just-the-docs rake search:init
  ```

3. Run you local Jekyll server
  ```bash
  $ jekyll serve
  ```
  ```bash
  # .. or if you're using a Gemfile (bundler)
  $ bundle exec jekyll serve
  ```

4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.


---

## About the project

Notion User Guide is &copy; 2022-{{ "now" | date: "%Y" }} by Lost Ark Studio.

### License

Just the Docs is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### About our team.



#### Thank you for checking out Lost Ark Studio!

<ul class="list-style-none">

</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/just-the-docs/just-the-docs/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.
