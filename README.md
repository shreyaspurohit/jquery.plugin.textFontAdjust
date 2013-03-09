Jquery Text Font Adjust Plugin
==============================

It is sometime necessary that text font size adjusts and decreases based on the width and height of the containing container. This jquery plugin adjusts the font of the element so that it fits with in the container.

Usage
-----
Include the script in the head of the HTML page.
	<script language="javascript" type="text/javascript" src="jquery.textFontAdjust.js"></script>
	
On document ready or when needed call the plugin.
	$(parentContainer).textFontAdjust(textElement, options);

'parentContainer' is the container div that contains the text element 'textElement' which can be a label or a span containing text.
	
Options
-------
*	maxFontPerc: Int (in %)
	Default: 100
	The maximum font size in percentage that the text element can be sized to.
*	minFontPerc: Int (in %)
	Default: 25
	The minimum font size in percentage that the text element can be sized to.
*	additionalWidthToDecrease: Int
	Default: 0
	The additional width to decrease from the parent container width to consider in calculations. This is
	used generally when the parent container has more elements occupying the width other than the text
	element itself.
	
Live in Action
--------------
The plugin is used at http://sl.bitourea.com/ for the trending and realtime data. 

Licensing
---------
Released under MIT license, go ahead and use, modify, distribute as you wish. The license is provided in LICENSE.txt. The license of other libraries used must be used as defined by them. 	
