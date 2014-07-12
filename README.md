slide-switcher
==============

Polymer component for slide switching with animation and scroll events



Summary
--------------

Slide-switcher extends core-selector adding reaction to scroll and content animation (carousel on optimized css3).
It fits parent element but can by styled not to with position css styles.

```html
<slide-switcher valueattr="id" selected="{{s}}" selectedIndex="{{sI}}" noscroll>
	<slide-clip id="company">
    		Company
	</slide-clip>
	<slide-clip id="employees">
    		Employees
	</slide-clip>
	<slide-clip id="aboutus">
    		About Us
	</slide-clip>
</slide-switcher>
```

Attributes
-------------

noscroll - Boolean (Tag - if present scroll events are disabled)
