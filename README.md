# Templates by `jekyllgems`

This is a pinned repo to make it easier to locate themes and templates created for the jekyllgems org. If anything has issues or isn't working correctly please let me know in github Issues for the project itself. All of these are using [Bootstrap v5.3](https://getbootstrap.com) and [Font Awesome Icons v6.4.0](https://fontawesome.com). I will update this file as new themes are added. You can view the changelog for the org at https://changelog.jekyllgems.dev which details changes done on each theme and plugin. You can also provide feedback on the discord channel linked in the README on the front page.

## Installation

Themes have three methods of installation which is immediately confusing for newbies. I provide all three in each project so it is simple to use a method and remember it. 

- **As A Template:** This is the easiest method. Simply navigate to the repo homepage and click the button that says "Use This Template". It will prompt you to create a new repo under your account using this template. Then you just go to settings > pages and serve it up.
- **As A Gem:** Just change the line in your Gemfile for remote themes and use `gem "jekyll-base"` then when you `bundle install` it will add all the files you need.
- **Download:** Download the repo as a ZIP and then navigate to it and do `bundle install` then `jekyll serve`

## ["Jekyll Base" v0.0.2](https://github.com/jekyllgems/base)

This is just the bare bones Jekyll site. I update this periodically to add more posts. gh-pages doesn't allow many plugins so I only keep the bare minimum theme here so you can install it and use it in beginning jekyll sites instead of the minima theme. 

## ["Jekyll BS5" Starter Template v0.0.1](https://github.com/jekyllgems/bs5-starter)

This is the Bootstrap v5.3 starter template you can find in simple html on https://getbootstrap.com made into a jekyll theme. You can download it, use it as a template, and use it to create your own custom templates.