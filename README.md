#  Vikram Mahto | Mechanical Design Engineer Portfolio

This is the source code for my personal portfolio and engineering blog, hosted on [GitHub Pages](https://pages.github.com/). 

##  Built With
* **Framework:** [Jekyll](https://jekyllrb.com/)
* **Style:** Bootstrap & SCSS
* **Math Rendering:** MathJax (for engineering formulas)
* **Hosting:** GitHub Pages

---

##  How to Add Content

### 1. Creating a New Blog Post
All posts must be placed in the `_posts/` directory.
** IMPORTANT:** The filename **MUST** start with the date to work correctly.

* **Correct:** `2025-12-18-creo-toolkit.md`
* **Incorrect:** `creo-toolkit.md` (Will cause build error)

**Front Matter Template:**
Every post needs this header at the top:
```yaml
---
layout: post
title: "Your Post Title Here"
date: 2025-01-01 10:00:00
permalink: /blog/your-url-slug/
description: "A short summary for the preview card."
tags: fea engineering ansys
categories: engineering
---
2. Adding Images
Location: Store images in assets/img/folder-name/.

Preview Image: Always include a preview.jpg in that folder for the blog card.

Side-by-Side Images: Use the custom HTML snippet below for comparison views (like the Conservator post):
<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
  <div style="flex: 1; min-width: 300px; text-align: center;">
     <img src="/path/to/image1.jpg" style="width: 100%;">
  </div>
  <div style="flex: 1; min-width: 300px; text-align: center;">
     <img src="/path/to/image2.jpg" style="width: 100%;">
  </div>
</div>

Design & Customization
Color Scheme
Primary Blue: #007bff (Used for Links, Nav, Progress Bar, and Blockquotes)

Background: White / Light Grey #f1f3f5

Key Configuration Files
_config.yml: Main settings (Site Title, Description, Favicon path).

_pages/blog.md: Controls the main Blog feed layout.

_layouts/post.liquid: Contains the Global CSS overrides for:

Blue Blockquote lines

Blue Reading Progress Bar

Image responsive sizing

Favicon
The site icon uses a custom Blue Gear instead of the default theme emoji.

File: assets/img/favicon.ico

Config Setting: icon: assets/img/favicon.ico
Running Locally
To test changes on your computer before pushing to GitHub:

Install Prerequisites: Ruby and Jekyll.

Install Gems:

Bash

bundle install
Run Server:

Bash

bundle exec jekyll serve
View Site: Open http://localhost:4000 in your browser.

License
This project is open source and available under the MIT License.
