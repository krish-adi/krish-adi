# krishadi.com 

## This repository stores the build files for krishadi.com, my personal blog. 

The theme [jekyll-book](https://github.com/krish-adi/jekyll-book) is used here.

## w/ Obsidian

I have set this up to se with [obsidian](obsidian.md). It uses the templater community plugin, and the templates are located inside `_templates`.

## Working on posts

- markdown cheatsheet
- Python setup and environments
- vue-js build commands
- ruby setup and environments
- greppo demo app

## Usage

Posts are within the folder `_posts`. Use the folder structure based on the category of the post. The mandatory index file `0000-01-01-index.md` inside the category folder within posts.

   `_posts/:category/0000-01-01-index.md`

   With contents:

   ```md

   ---
   title: index
   date: 0000-01-01
   category: code
   layout: category-index
   ---

   ```
   
> To build the blog and serve it locally, run `bundle exec jekyll serve`.
