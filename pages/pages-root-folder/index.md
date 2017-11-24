---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: homepage_header.jpg
widget1:
  title: "Develop"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: develop_widget.jpg
  text: 'We develop innovative systems and processes for efficient data collection, promotion of data value and implementation into fisheries management systems.'
widget2:
  title: "Apply"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'We apply these systems and processes to provide stock and/or fishery-specific research services that support timely and efficient fisheries management decision making.'
  image: apply_widget.jpg
widget3:
  title: "Collaborate"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: collaborate_widget.jpg
  text: 'We carry out these activities in a manner that efficiently utilises industry resources, and supports industry involvement in fisheries management processes.'
widget4:
  title: "Support"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: support_widget.jpg
  text: 'We ensure a broad base of industry commitment to the development of its systems and processes, and the utilisation of the results of applying these systems and processes.'
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
permalink: /index.html
---


<div class="medium-6 medium-push-6 columns">
<h3>About Us</h3>
<p>Find out more about who is part of the Trident Systems team and how we go about developing our work as well as who else we work with.</p>
<p><a class="button tiny radius" href="{{ site.url }}{{ site.baseurl }}/about-us/">{{ site.data.language.more }}</a></p>
</div>
<div class="medium-6 medium-pull-6 columns">
<h3>Our Work</h3>
<p>Find out more about who is part of the Trident Systems team and how we go about developing our work as well as who else we work with.</p>
<p><a class="button tiny radius" href="{{ site.url }}{{ site.baseurl }}/about-us/">{{ site.data.language.more }}</a></p>
  </div>
