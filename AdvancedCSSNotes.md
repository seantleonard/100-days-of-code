The easiest way to center anything is with the transform, top, and left properties.

alt attribute is to describe image for SEO. And in case image fails to load. Instead of image, the text loads. 

Next section: difference between absolute and relative positioning. NOrmal flow and floats. 

Top, bottom, left properties to put image where it needs to be .
Measurement starts from somewhere, must be  frame of reference. The reference is the parent element whose position is set to relative. 

For logo image, specify height, and width is then figured out by the browser and vice versa. 

for our heading, we want two lines in our page. H1 is important for Google (Search Engine) to figure out what our page is about. We could do h1 for main line, and h2 for sub line.  But we may not want our text split up or only set as one word in h1. So we use the Span element. Use one span element for the top and a second span element for the bottom. Span is an inline element, just like text. Use display propery. 

https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements

https://developer.mozilla.org/en-US/docs/Web/CSS/Containing_block

https://developer.mozilla.org/en-US/docs/Web/CSS/position

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context
    Stacking context. z-coordinate. 

Best way to center text box: absolute positioning. But what if we want our text to be right in the center of the page instead of 50% from left and top of parent element? Because this leaves the text box looking off center. however, the start of the element is correctly in the center. 

transform: translate(-50%, -50%);
translate x and y. The 50% are no longer in relation to the parent element but to the element itself. If we want -50%, it will be shifted half of the width to the left side. same for the height. -50% means it will be shifted 50% of the element's height to the top. if transform property has value other than none, a stacking context will be created, so that the transform does not affect other elements on the page. 

https://developer.mozilla.org/en-US/docs/Web/CSS/transform

2.8: Creating Cool CSS Animations

Two types of css animations
transition property

Keyframes:
@keyframe <name> {
    and now you specify what happens in each moment of the animation. 
}
translateX animates in the x direction from left to right. If the px or % is positive, then the element will animate from right to left as you think of a number line in the x axis. If the px or % is negative, then the element will animate from left to right. 
translateY animates in the y direction from top to bottom.

translate(0) looks the way that it looks originally. 

You have to specify the animation-name and then the animation-duration in the element you want to animate. 

You can also set animation-delay. But that doesn't look good here. Could be useful sometimes. 

Animation-iteration-count: X. set to value, and the animation will happen X times. 

Animation-timing-function: ease
https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function

animation: name duration timing-function delay iteration-count direction fill-mode play-state;
https://www.w3schools.com/cssref/css3_pr_animation.asp