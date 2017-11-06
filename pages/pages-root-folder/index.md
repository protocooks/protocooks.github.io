---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-frank-1600x503.jpg
widget1:
  title: "Class and Demos"
  url: '/events/'
  image: widget-1-302x182.jpg
  text: 'Learn to cook with Chef Frank. He knows his shit.'
widget2:
  title: "Catering"
  url: '/catering/'
  text: 'Want something incredibly tasty to eat at your next event?'
  image: widget-catering-303x182.jpg
widget3:
  title: "Chef Frank's Blog"
  url: '/blog/'
  text: "What's Chef Frank up to these days?"
  image: widget-blog-303x182.jpg
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
  url: /events/
  text: Chef Frank is ready to feed you ›
  style: alert
# 
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
