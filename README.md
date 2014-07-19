slide-switcher
==============

Polymer carousel component with animation and scroll events



Summary
--------------

Slide-switcher extends [core-selector](https://github.com/Polymer/core-selector) adding content animation and reaction to scroll.
For proper display it needs to be styled with width and height or Polymer fit attribute (or to be part of container with defined layout).

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

noscroll - Boolean (disables scroll events)
