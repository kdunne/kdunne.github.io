---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
widget1:
  title: "ATLAS Pixel Detector Electronics"
  url: 'http://kdunne.github.io/pixel/'
  image: fei4b-size.jpg 
  text: 'Quad modules of FEI4B and RD53A chips for testing serial powering of Pixel detector modules'
widget2:
  title: "ATLAS Hadronic Calorimeter Electronics"
  url: 'http://kdunne.github.io/tile/'
  text: 'PCBs to test upgrades to test remote JTAG control'
  image: proasic.jpg 
widget3:
  title: "Crystalline Xenon Time Projection Chamber"
  url: 'http://kdunne.github.io/crystallize/'
  image: crystalize.jpg
  text: 'Detecting scintillation in solid xenon with Silicon Photomultipliers'
widget4:
  title: "Neutron-Antineutron Annihiliation Detector"
  url: 'http://kdunne.github.io/nbar/'
  image: nnbar.jpg 
  text: ''
widget5:
  title: "Axion Plasma Haloscope"
  url: 'http://kdunne.github.io/crystallize/'
  image: 
  text: ''
widget6:
  title: "PWR Effects Pedal Set"
  url: 'http://kdunne.github.io/pwr/'
  image: 
  text: ''

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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert

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
