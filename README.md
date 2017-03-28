# CoinCulture

## To run from a local server
1. Make sure you have Hugo installed.
2. Clone
3. ```$ hugo server```
4. Access at localhost:1313

## To add content
1. In working dir, input ```$ hugo new blog/blog title.md```
2. Fill out TOML front matter. Fairly self explanatory..
  - 'categories' will add new categories to 'categories' section (can be more than one and should be formatted as ```categories: ['cat1','cat2']```)
  - ```featuredpath``` is for main image path. Images must be put in ```/static/img```, and file path is to be written as ```img/filename.extension```
3. Fill out body below ```+++``` in Markdown.
