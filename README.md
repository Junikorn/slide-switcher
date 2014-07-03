slide-switcher
==============

Polymer component for slide switching with animation



Summary
--------------

Slide-switcher creates core-selector-like element which can change state in reaction to scroll animating content (it also uses selected attribute and allows to disable scroll events). It fits parent element but can by styled not to with position css styles.

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

Attributes
-------------

selected - String (Value of specified attribute of selected clip (or if no valueattr set selectedIndex))

selectedIndex - Number (Index of selected clip)

valueattr - String (Name of attribute of clip on basis of which selection is made)

noscroll - Boolean (Tag - if present scroll events are disabled)
