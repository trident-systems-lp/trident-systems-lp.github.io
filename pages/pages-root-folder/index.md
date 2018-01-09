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
  url: '/our-work/'
  image: develop_widget.jpg
  text: 'We develop innovative systems and processes for efficient data collection, achieving greater value from data, and implementing effective fisheries management.'
widget2:
  title: "Apply"
  url: '/our-work/'
  text: 'We apply these systems and processes to provide stock and/or fishery-specific research services that support timely and efficient fisheries management decision making.'
  image: apply_widget.jpg
widget3:
  title: "Collaborate"
  url: '/about-us/approach/'
  image: collaborate_widget.jpg
  text: 'We carry out these activities in collaboration with other researchers, efficiently utilising industry resources, and supporting industry involvement in fisheries management processes.'
widget4:
  title: "Support"
  url: '/about-us/'
  image: support_widget.jpg
  text: 'We ensure a broad base of industry commitment to the development of our systems and processes, and using the results generated.'
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
homepage: true
---


<div class="medium-6 medium-push-6 columns">
  <h3>About Us</h3>
    <p>Find out more about the philosophy and structure of Trident Systems, the members of our team, and who we work with.</p>
    <p><a class="button tiny radius" href="{{ site.url }}{{ site.baseurl }}/about-us/">{{ site.data.language.more }}</a></p>  
</div>

<div class="medium-6 medium-pull-6 columns">
  <h3>Our Work</h3>
    <p>Find out more about the projects undertaken by Trident Systems, how we work, and the systems and processes we have developed.</p>
    <p><a class="button tiny radius" href="{{ site.url }}{{ site.baseurl }}/our-work/">{{ site.data.language.more }}</a></p>
</div>
