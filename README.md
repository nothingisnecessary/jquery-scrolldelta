# jquery-scrolldelta
simple jQuery `scrolldelta` event plugin that is used in place of the `scroll` event to include the amount scrolled in pixels

## example

[JS Fiddle](http://jsfiddle.net/tew9zxc1/)

$(window).on("scrolldelta", function(e)
{
    var top = e.scrollTop;
    var topDelta = e.scrollTopDelta;
    var left = e.scrollLeft;
    var leftDelta = e.scrollLeftDelta;
	
	// your sweet ass code goes here
});


## requires

jQuery 1.0 or later (I think; not confirmed, but recent versions work)

