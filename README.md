blazy.js
========

Fork of bLazy.js by © Bjoern Klinggaard adapted for all browsers.

bLazy is a lightweight script for lazy loading and multi-serving images (less than 3.5KB minified). It’s in pure JavaScript why it doesn’t depend on 3rd-party libraries such as jQuery. It lets you lazy load and multi-serve your images so you can save bandwidth and server requests. The user will have faster load times and save data usage if he/she doesn't browse the whole page.

[Documentation](http://dinbror.dk/blazy/ "See online") 

Support for old browsers added: 

bLazy changes placeholder image src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" with your full size images links instead for backwards compatibilities in old browsers but modern browsers don't load images until users scroll down. 
i.e.

    <div class="pics ratio_small-img">
			<img class="b-lazy" src="http://dinbror.dk/blazy/assets/bears/big-bear1.jpg" data-src="http://dinbror.dk/blazy/assets/bears/bear-small1.jpg" alt="Lazy load images small image1" />
		</div>

Displays images if javascript is disabled. Displays images in old browsers. Uses a tiny image of one pixel as substitution in Base64 encoded format. Simple usage with a class name.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/cara-tm/blazy.js/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

