css-js-helpers-libs
===================

List of css, js libs and frameworks

## Extras
* [APE (Ajax Push Engine)](http://ape-project.org/)

* [7 Habits of Highly Effective Media Queries](http://bradfrost.com/blog/post/7-habits-of-highly-effective-media-queries/)

##### CSS

* IE css trick
```java
<!--[if IE 7]><html xmlns="http://www.w3.org/1999/xhtml" class="ie ie7"><![endif]-->
<!--[if IE 8]><html xmlns="http://www.w3.org/1999/xhtml" class="ie ie8"><![endif]-->
<!--[if IE 9]><html xmlns="http://www.w3.org/1999/xhtml" class="ie ie9"><![endif]-->
<!--[if gt IE 9]><html xmlns="http://www.w3.org/1999/xhtml" class="ie"><![endif]-->
<!--[if !IE]><!--><html xmlns="http://www.w3.org/1999/xhtml"><!--<![endif]-->
```

* [Pure CSS Parallax Websites](http://keithclark.co.uk/articles/pure-css-parallax-websites/)

##### PHP

* [PHP Simple HTML DOM Parser](http://simplehtmldom.sourceforge.net/)

* [Slim: PHP micro framework that helps you quickly write simple yet powerful web applications and APIs](http://www.slimframework.com/)

* [PHP client for Yahoo Finance API](https://github.com/scheb/yahoo-finance-api)

* [CodeIgniter is a powerful PHP framework with a very small footprint](http://www.codeigniter.com/)

* [CodeIgniter: plugins](https://github.com/bcit-ci/CodeIgniter/wiki/_pages)

* [CodeIgniter: Ion Auth Lightweight Auth System](https://github.com/benedmunds/CodeIgniter-Ion-Auth)

##### PhoneGap/Cordova
* [PayPal SDK Cordova/Phonegap Plugin](https://github.com/paypal/PayPal-Cordova-Plugin)

* [Pushwoosh Push Notifications plugin](https://github.com/Pushwoosh/pushwoosh-phonegap-3.0-plugin)

## CSS
* [Animate.css: Just-add-water CSS animations](http://daneden.github.io/animate.css/)
```javascript
// Animate.css if you need a callbacks
$('div').addClass('animated flip')
       	.one('webkitAnimationStart mozAnimationStart MSAnimationStart oanimationstart animationstart', function () {
        	console.log('Animation Started');
       	})
       	.one('webkitAnimationIteration mozAnimationIteration MSAnimationIteration oanimationiteration animationiteration', function () {
            console.log('Animation Step');
        })
        .one('webkitAnimationEnd mozAnimationEnd MSAnimationEnd oanimationend animationend', function () {
        	console.log('Animation Ends');
        });
```

* [Movies In Color: Films and their corresponding color palettes](http://moviesincolor.com/)

* [Leshy SpriteSheet Tool: Online](http://www.leshylabs.com/apps/sstool/)

* [Purecss.io: A set of small, responsive CSS modules that you can use in every web project](http://purecss.io/)

* [Font Awesome](http://fortawesome.github.io/Font-Awesome/)

* [Page Transitions](https://github.com/codrops/PageTransitions)

## Javascript
* [Ionic Framework: The beautiful, open source front-end SDK for developing hybrid mobile apps with HTML5](http://ionicframework.com/)

* [Ionic Examples](http://codepen.io/ionic/)

* [Ionic Creator: Create great Ionic apps with a flick of the wrist](https://creator.ionic.io/app/login)

* [ngCordova: Set of AngularJS extensions on top of the Cordova API](http://ngcordova.com/)

* [Foundation: The most advanced responsive front-end framework in the world](http://foundation.zurb.com/)

* [Phaser.io: Game framework for making desktop and mobile browser HTML5 games](http://phaser.io/)

* [Popcorn.js: The HTML5 Media Framework](http://popcornjs.org/)

* [Parallax.js: reacts to the orientation of your smart device](http://matthew.wagerfield.com/parallax/)

* [Hammer.js: Add touch gestures to your page](http://hammerjs.github.io/)

* [Retina.js: Retina graphics for your website](http://imulus.github.io/retinajs/)

* [Moment.js: Parse, validate, manipulate, and display dates in JavaScript](http://momentjs.com/)

* [Moment.js Timezone: Parse and display dates in any timezone](http://momentjs.com/timezone/)

* [XDate: A Modern JavaScript Date Library](http://arshaw.com/xdate/)

* [Fullcalendar.io: A JavaScript event calendar. Customizable and open source](http://fullcalendar.io/)

* [Video.js: The open source HTML5 video player](http://www.videojs.com/)

* [PhotoSwipe: IMAGE GALLERY FOR MOBILE AND TOUCH DEVICES](http://photoswipe.com/)

* [Chartist.js: SIMPLE RESPONSIVE CHARTS](http://gionkunz.github.io/chartist-js/)

* [Victor.js: A JavaScript 2D vector maths library for Node.js and the browser](http://victorjs.org/)

* [Lo-Dash: A utility library delivering consistency, customization, performance, & extras](https://lodash.com/)

* [WYSIWYG: TinyMCE](http://www.tinymce.com/)

* [jSignature  Draw signature in the browser](http://willowsystems.github.io/jSignature/#/about/)

## jQuery plugins
* [jQuery UI Touch Punch: Touch Event Support for jQuery UI](http://touchpunch.furf.com/)

* [w2ui: jQuery plugins for front-end development of data driven web applications](http://w2ui.com/web/)

* [jQuery Knob: Nice, downward compatible, touchable, jQuery dial](http://anthonyterrien.com/knob/)

* [Velocity.js: Accelerated JavaScript animation](http://julian.com/research/velocity/)
```javascript
// Register Velocity.js a custom UI pack effect
$.Velocity.RegisterUI('callout.twirl', {
    defaultDuration: 3000,
    calls: [ 
			[ { rotateZ: 1080 }, 0.50 ],
			[ { scaleX: 0.5 }, 0.25, { easing: 'spring' } ],
			[ { scaleX: 1 }, 0.25, { easing: 'spring' } ]
    ]
});

$('div').velocity('callout.twirl');
```
* [jqPlot: A Versatile and Expandable jQuery Plotting Plugin](http://www.jqplot.com/)
