# D3-anim-mashup

The animated bar graph was adapted from Anthony Skelton's codepen: http://codepen.io/ajskelton/pen/Lkniv
The smooth scrolling code was taken from Chris Coyier's codepen: http://codepen.io/chriscoyier/pen/dpBMVP
Code for determining whether the element is in view adapted from this stackoverflow answer: http://stackoverflow.com/questions/123999/how-to-tell-if-a-dom-element-is-visible-in-the-current-viewport/7557433#7557433

This is a simple page that utilises smooth scrolling to easily (and smoothly!) jump between sections and waits for the empty div to be visible in the viewport before drawing the bar graph.


With the code sort of Frankenstein's monster'd as it is, building on this foundation could become pretty messy pretty fast. If I wanted to use this method to draw in lots of different animations at different points I'd probably try to pare the code down to its essentials. I am definitely using the smooth scrolling going forward, though.
