---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title               : "PEKOE EARTHNODE"
subheadline         : "Official WorldMobile EarthNode"
teaser              : "World Mobile Chain is the first dedicated telecoms blockchain. An EVM-compatible Layer 3, built on Base, enabling fast, secure and affordable transactions, with easy-to-deploy decentralized applications."
header:
  image_fullwidth: pekoex.jpg
widget1:
  title: "Revolutionizing how the world connects"
  url: 'https://earthnodepekoe.github.io/blog/'
  image: puny 300x200.jpg
  text: 'Innovation should serve humanity—not corporations. Mobile networks are essential in today’s world, yet we’ve surrendered control to Big Wireless, which profits from our data while leaving half the world disconnected and many major cities with unreliable coverage. The digital world is evolving, but mobile networks remain stuck in the past. You’re paying more for less, with limited coverage and your personal data being treated like a commodity. Privacy is a right, not a privilege. Enough is enough. It’s time for a mobile network that works for you, not against you.'
widget2:
  title: "Why stake with us?"
  url: '/getting-started/'
  text: '<em>   </em> <br/>1. Reliable Infrastructure – Our node is monitored 24/7 to ensure uptime and efficiency.<br/>2. Decentralization First – We uphold the true spirit of blockchain, contributing to a robust and distributed World Mobile ecosystem.<br/>3. Impact Staking – Your rewards fuel real-world change by connecting tea-growing communities to the future.<br/>4. Transparency & Community Focused – Regular updates, governance participation, and an open communication policy.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://earthnodepekoe.github.io/images/cap video 300x200.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "A mobile network that puts you in control"
  url: 'https://earthnodepekoe.github.io/blog/'
  image: movil 300x200.jpg
  text: 'We’re building a decentralized mobile network—owned and operated by the people, for the people, everywhere. From bustling cities to the most remote corners of the world, we’re connecting everyone, ensuring no one is left behind. This is connectivity on your terms. Join the movement and reclaim power over your mobile experience. Imagine a mobile network that delivers reliable connectivity everywhere, a network that rewards you for participating and gives you power over your privacy and data.'
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
  url: https://earthnodepekoe.github.io/getting-started
  text: STAKE NOW WMTx
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
{% include alert warning='This is a warning.' %}

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/xjF5iXcAaSY?feature=shared" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
