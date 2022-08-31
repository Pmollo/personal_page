# SitePerso

## How to build it

For the full instruction go to [Jekyll website](https://jekyllrb.com/).
In this current version, if Ruby (version > 2.5) is installed, 
run (only the first time):

````[bash]
bundle
````

Then to build the site run:

````[bash]
bundle exec jekyll build
````
 this shall creat (or update) the `_site` folder containing the 
ouput site.
In order to have a site preview, run:

````[bash]
bundle exec jekyll serve --livereload
````

and open the given link with your web browser, the site is still local
at this point.


