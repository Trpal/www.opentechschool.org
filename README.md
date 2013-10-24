# [www.opentechschool.org](http://www.opentechschool.org)


The source code behind OTS' main web site.

This project is built with the help of 

 * bootstrap
 * compass
 * jekyll

In order to be able to compile the site on your own computer, you can install 
the two ruby dependencies with `bundle install` if you have bundler.

## Building the site

1. run `bundle install` to grab ruby dependencies
2. `rm -rf _site/*`
3. `compass clean; compass compile` (you can leave compass running while editing styles with `compass watch`)
4. `jekyll serve -w`
5. Navigate to http://localhost:4000
