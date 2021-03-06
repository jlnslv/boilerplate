Web development boilerplate
===========

This is a HTML boilerplate for my private projects.

## Getting Started / Dependencies
This plugin requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this boilerplate with this command:

``` shell
npm install
```

Running the dev server requires you to have [Ruby](http://www.ruby-lang.org/en/downloads/), [Sass](http://sass-lang.com/tutorial.html), and [Compass](http://compass-style.org/install/) >=0.12.2 installed. If you're on OS X or Linux you probably already have Ruby installed; test with `ruby -v` in your terminal. When you've confirmed you have Ruby installed, run `bundle install` to install Compass and Sass.

Run a dev server (with livereload):
``` shell
grunt server
```

Run a dist server (minified assets):
``` shell
grunt server:dist
```

## How-to
The `index.html` in the `app` directory is your development file.  The development assets folder are within the `assets` folder.

The idea is that all your assets will be concatenated, minified and optimized into the `prod` folder using the following command:
``` shell
grunt build
```
or 
``` shell
grunt server:dist
```


### Add new JavaScript Plugin
New plugins have to added through bower. I've added the follow `grunt plugin` https://github.com/stephenplusplus/grunt-bower-install. It injects components automagically into the index.html (not the one in `public`)

## The MIT License (MIT)

Copyright (c) 2013 Julien Silva

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
