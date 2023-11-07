# center-mobile-button

I noticed some odd behavior with buttons on mobile web browsers when trying to create a simple circular button with a plus sign centered inside of it.

This site is here to demonstrate the behavior, and all of the strategies I used to solve the problem.



It seems using an SVG to achieve this is a common practice (Facebook Discord, and Bootstrap all use SVGs for this). 

However, using 'before' and 'after' pseudo-elements also produced the desired result.

Note that this behavior ONLY happens on mobile browsers, not in Chrome DevTools' mobile views.
