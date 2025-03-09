+++
date = '2025-02-23T23:01:11+08:00'
draft = false
title = 'Init Draft'
+++

### After setting it up, it works locally but not on GitHub Pages
<!--more-->
When running hugo server -D in the local terminal, the draft content is accessible in the browser as expected. However, after uploading to GitHub, it doesn't work.

The issue doesn't seem to be with GitHub Actions.

I searched online and tried various solutions. Initially, I used Hugo to compile the site, but it didn’t work. Later, I changed the draft value to false in the front matter of each article, and then it worked.

The official documentation also mentions this:

Notice the draft value in the front matter is true. By default, Hugo does not publish draft content when you build the site. Learn more about draft, future, and expired content.