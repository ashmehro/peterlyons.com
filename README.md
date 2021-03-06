# peterlyons.com web site

This repo contains a node.js/express.js web application I use to power my personal/professional web site at [http://peterlyons.com](http://peterlyons.com).

Basically, the site supports content in the following formats:

 * static html pages
 * pages written in [jade](https://github.com/visionmedia/jade)
 * pages written in [markdown](http://daringfireball.net/projects/markdown/)
 * a basic blog engine
   * Includes an ATOM feed
   * Allows posts in HTML or markdown
   * contains some DSL magic HTML-ish tags to reduce boilerplate
   * has a handy output pipeline
 * a simple photo gallery system

Over the years, I've tried out various deployment methodologies and file layouts. I tried a full-on static site generator with all the generated files in the git repo, and have now decided I do not like that approach. Thus this site serves dynamic content primarily with tiny bits of caching at the few spots where we get decent bang for our caching buck.

#Related repositories

The site requires 3 git repositories to fully function

1. The code (this repository)
2. The data (blog posts and photo gallery metadata)
3. Static files (images, fonts, etc)

Since the data and static repos aren't very interesting, I don't publish them on github. All the interesting code is in this repository.

#License: MIT
Copyright (c) 2013 Peter Lyons

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
