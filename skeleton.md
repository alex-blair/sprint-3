What happens to the layout when you resize the screen to less than 550px? How do you think that works?

As you shrink the page content is rearranged and certain elements change in size. At less than 550px, content is arranged in a way that makes it easy to read on a mobile browser, with images and text centred but still large enough to read. Skeleton uses media queries as well as rems (which are relative units) so that font-sizes and spacial relationships responsively adjust depending on the size of the browser. The media queries Skeleton uses are mobile-first, which means they target min-width. In this case there are three different sizes at which new styling rules start to apply: bigger than 550px, bigger than 750px, and bigger than 1000px.

As an example, a media query is used to make the font at the top of the page ("Stop coding non-responsive sites...") responsive.
At less than 550px, a default sizing rule applies. At a min-width of 550px, a new media query/rule kicks in giving the text a font-size of 2.4rem, and at a min-width of 750px, the size increases again to 2.6px. Small changes like these help to ensure that the content fills up the space on bigger browser windows. 
