css-js-helpers-libs
===================

List of css, js libs and frameworks

## CSS
* [Animate.css: Just-add-water CSS animations](http://daneden.github.io/animate.css/)
```javascript
// Animate.css if you need a callbacks
$('div').addClass('animated ' + 'flip')
       	.one('webkitAnimationStart mozAnimationStart MSAnimationStart oanimationstart animationstart', function () {
        	console.log('Animation Started');
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

* [Ionic Creator: Create great Ionic apps with a flick of the wrist](https://creator.ionic.io/app/login)

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

## jQuery plugins
* [jQuery UI Touch Punch: Touch Event Support for jQuery UI](http://touchpunch.furf.com/)

* [w2ui: jQuery plugins for front-end development of data driven web applications](http://w2ui.com/web/)

* [jQuery Knob: Nice, downward compatible, touchable, jQuery dial](http://anthonyterrien.com/knob/)

* [Velocity.js: Accelerated JavaScript animation](http://julian.com/research/velocity/)
```javascript
// Register Velocity.js a custom UI pack effect.
$.Velocity.RegisterUI('callout.twirl', {
    defaultDuration: 3000,
    calls: [ 
			[ { rotateZ: 1080 }, 0.50 ],
			[ { scaleX: 0.5 }, 0.25, { easing: "spring" } ],
			[ { scaleX: 1 }, 0.25, { easing: "spring" } ]
    ]
});

$('div').velocity('callout.twirl');
```
