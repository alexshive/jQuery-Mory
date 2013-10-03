# [jQuery Mory - A Read More Plugin](http://wbotelhos.com/mory)

jQuery Mory is a plugin to resume texts along with a read more link. Updated to use CSS properties. Tested working with **jQuery v1.10.2**

## License

The jQuery Mory is licensed under [The MIT License](http://www.opensource.org/licenses/mit-license.php)

## Version

	@version        0.2.0
	@since          2012.01.07
	@author         Washington Botelho
	@documentation  wbotelhos.com/mory
	@twitter        twitter.com/wbotelhos

## Required Files

	jquery.min.js
	jquery.mory.js

## Default values

	useClasses		: false
	collapseText	: 'read less'
	expandText		: 'read more'
	reticence		: '... '
	size			: 140

## Usage

### Default

	$('#text').mory();

	<div id="text"></div>

### Custom numbers of characters displayed:

	$('#text').mory({
	    size: 255
	});

### Use CSS instead of Javascript:

	$('#text').mory({
	    useClasses : true
	});

### Custom label for show more or less text:
	$('#text').mory({
    	expandText   : 'show more',
	    collapseText : 'show less'
	});

### Custom reticence element:

$('#text').mory({
    reticence: ' [...] '
});

### Changing the settings globally:

	$.fn.mory.defaults.size = 255;
	$.fn.mory.defaults.reticence = ' [...] ';

+ You can change any option mention the scope `$.fn.mory.defaults. + option_name;`
+ This setup must be called before you bind the Mory, of course.


## Buy him a coffee (not me)

You can do it by [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=X8HEP2878NDEG&item_name=jQuery%20Mory). Thanks! (:
