---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: d_header_newtons_cradle.jpg
widget1:
  title: "Blog"
  url: '/blog/'
  image: d_widget_blog_300x225.jpg
  text: "Every good website has a blog.  This one is mine.  It's full of my losely organized ramblings along with other goodness.  Click around! Stay a while!  Enjoy!"
widget2:
  title: "Newsletters"
  url: '/newsletters/'
  image: d_widget_newsletters_300x221.jpg
  text: "All the news that's fit to print... ok, a bunch of the news that I saw fit to link to."
widget3:
  title: "Code Samples"
  url: 'https://github.com/deversmann'
  image: d_widget_github_300x217.jpg
  text: "Check out my github repos for the things I'm working on.  It's full of demos, configs and generally a bunch of interesting stuff."
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /moshpit
  text: Find out about MOSH>pit w/Damien ≫
  style: alert

permalink: /index.html

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/HA4ccCVCglw" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
