blazy.js
========

For of Blazy.js by © Bjoern Klinggaard adapted for all browsers.

bLazy is a lightweight script for lazy loading and multi-serving images (less than 3.5KB minified). It’s in pure JavaScript why it doesn’t depend on 3rd-party libraries such as jQuery. It lets you lazy load and multi-serve your images so you can save bandwidth and server requests. The user will have faster load times and save data usage if he/she doesn't browse the whole page.

Support for old browsers added: 

change placeholder image src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" with your full size images links instead for backwards compatibilities in old browsers but modern browsers don't load images before users scroll down. i.e.

    <div class="pics ratio_small-img">
			<img class="b-lazy" src="http://dinbror.dk/blazy/assets/bears/big-bear1.jpg" data-src="http://dinbror.dk/blazy/assets/bears/bear-small1.jpg" alt="Lazy load images small image1" />
		</div>
