# TNW Social Count
> Version: 1.0

[TNW](https:thenextweb.com) Social Count is a [WordPress](https://wordpress.com) plugin that solves the problem of social sharing the proper way. No more third-party scripts that slow down your site and ugly buttons that clutter your design.

The plugin has two parts: The backend part saves the number of Twitter retweets, Facebook likes, Google Plus and LinkedIn shares as
`post_meta` information. 

The frontend part renders a share button on the same fashion as on [The Next Web blog](https://thenextweb.com). 


## Installation
After activating the plugin, just include the following snippet of code in your theme, wherever you want the button to appear:

```php
<?php 
	if(function_exists('render_tnwsc_button')) {
		echo render_tnwsc_button();
	}
?>
```

## Author
- [Pablo Román](https://github.com/pabloroman) for [The Next Web](https://github.com/thenextweb)
