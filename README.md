css-js-helpers-libs
===================

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C2HFZWSUPV47Q" target="_blank">
  <img src="https://raw.githubusercontent.com/Blah2014/phonegap-inmobi-plugin/gh-pages/images/BuymeaCoffee.png" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!" />
</a>

List of css, js libs and frameworks

## Extras
* [APE (Ajax Push Engine)](http://ape-project.org/)

* [7 Habits of Highly Effective Media Queries](http://bradfrost.com/blog/post/7-habits-of-highly-effective-media-queries/)

* [PLACEHOLD.IT: A quick and simple image placeholder service](http://placehold.it/)
```java
// PLACEHOLD.IT Example
http://placehold.it/136x136/09f/fff.png&text=136x136
```

* [Online bitmap font generator](http://kvazars.com/littera/)

* [Tournament Bracket Generator](https://gist.github.com/sterlingwes/4199115)

##### CSS

* IE css trick
```java
<!--[if IE 7]><html xmlns="http://www.w3.org/1999/xhtml" class="ie ie7"><![endif]-->
<!--[if IE 8]><html xmlns="http://www.w3.org/1999/xhtml" class="ie ie8"><![endif]-->
<!--[if IE 9]><html xmlns="http://www.w3.org/1999/xhtml" class="ie ie9"><![endif]-->
<!--[if !IE]><!--><html xmlns="http://www.w3.org/1999/xhtml"><!--<![endif]-->

Note: Internet Explorer 10 No Longer Support Conditional Comments
```

* [Pure CSS Parallax Websites](http://keithclark.co.uk/articles/pure-css-parallax-websites/)

* [Simple Styles for <hr>'s](https://css-tricks.com/examples/hrs/)

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

* [CCA: Cordova Chrome App](https://developer.chrome.com/apps/chrome_apps_on_mobile)

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

* [FlatIcon: The largest database of free vector icons](http://www.flaticon.com/)

* [Page Transitions](https://github.com/codrops/PageTransitions)

* [WEBFONT GENERATOR: fontsquirrel.com](http://www.fontsquirrel.com/tools/webfont-generator)

## Javascript
* [Ionic Framework: The beautiful, open source front-end SDK for developing hybrid mobile apps with HTML5](http://ionicframework.com/)

* [Ionic Examples](http://codepen.io/ionic/)

* [Ionic Creator: Create great Ionic apps with a flick of the wrist](https://creator.ionic.io/app/login)

* [Ionic-Cli: The Ionic Framework command line utility](https://github.com/driftyco/ionic-cli)

* [ion-affix: Sticky affix elements for Ionic framework](https://github.com/aliok/ion-affix)

* [Foundation: The most advanced responsive front-end framework in the world](http://foundation.zurb.com/)

* [Phaser.io: Game framework for making desktop and mobile browser HTML5 games](http://phaser.io/)

* [Phaser.io: State Transition Plugin](https://github.com/cristianbote/phaser-state-transition)

* [Phaser.io - MIGHTYEDITOR: Web based open source HTML5 game editor](http://mightyfingers.com/)

* [Popcorn.js: The HTML5 Media Framework](http://popcornjs.org/)

* [Parallax.js: reacts to the orientation of your smart device](http://matthew.wagerfield.com/parallax/)

* [Leaflet: An Open-Source JavaScript Library for Mobile-Friendly Interactive Maps](http://leafletjs.com/)

* [Hammer.js: Add touch gestures to your page](http://hammerjs.github.io/)
```javascript
// Create Hammer custom gestures events
var myElement = document.getElementById('myElement');

// create a simple instance
// by default, it only adds horizontal recognizers
var mc = new Hammer.Manager(myElement);

mc.add(new Hammer.Swipe({ event: 'swipe', pointers: 1 }));

mc.add(new Hammer.Swipe({ event: 'twoswipe', pointers: 2 }));

// listen to events...
mc.on("swipe", function(ev) {
    myElement.textContent = '1 finger swipe: ' + ev.pointers.length;
    console.log(ev)
    
    setTimeout(function(){
      myElement.textContent = '';
    }, 3000);
});

mc.on("twoswipe", function(ev) {
    myElement.textContent = '2 finger swipe: ' + ev.pointers.length;
    console.log(ev)
    
    setTimeout(function(){
      myElement.textContent = '';
    }, 3000);
});
```

```javascript
// Swipe to delete
var mc = new Hammer.Manager(myElement);

mc.add(new Hammer.Pan({ 
  event: 'swipeRight', 
  pointers: 1,
  direction: Hammer.DIRECTION_RIGHT
}));


// listen to events...
mc.on("swipeRight", function(ev) {
  //console.log(ev);
  
  var elem = ev.target;
  elem.style.left = ev.deltaX + 'px';
  
  // Mobile
  elem.addEventListener('touchend', function(){
    setTimeout(function(){
      elem.style.left = '0px';
    }, 0);
    
  });
  
  // PC
  elem.addEventListener('mouseup', function(){
    setTimeout(function(){
      elem.style.left = '0px';
    }, 0);
    
  });
});
```

* [Retina.js: Retina graphics for your website](http://imulus.github.io/retinajs/)

* [Moment.js: Parse, validate, manipulate, and display dates in JavaScript](http://momentjs.com/)

* [Moment.js Timezone: Parse and display dates in any timezone](http://momentjs.com/timezone/)

* [XDate: A Modern JavaScript Date Library](http://arshaw.com/xdate/)

* [Fullcalendar.io: A JavaScript event calendar. Customizable and open source](http://fullcalendar.io/)

* [Video.js: The open source HTML5 video player](http://www.videojs.com/)

* [PhotoSwipe: IMAGE GALLERY FOR MOBILE AND TOUCH DEVICES](http://photoswipe.com/)

* [Chartist.js: SIMPLE RESPONSIVE CHARTS](http://gionkunz.github.io/chartist-js/)

* [Flot: Attractive JavaScript plotting for jQuery](http://www.flotcharts.org/)

* [Flot: Angular plugin (angular-flot: An Angular directive to wrap Flotcharts)](https://www.npmjs.com/package/angular-flot)

* [Victor.js: A JavaScript 2D vector maths library for Node.js and the browser](http://victorjs.org/)

* [Lo-Dash: A utility library delivering consistency, customization, performance, & extras](https://lodash.com/)

* [WYSIWYG: TinyMCE](http://www.tinymce.com/)

* [jSignature  Draw signature in the browser](http://willowsystems.github.io/jSignature/#/about/)

* [naturalSort.js: This will properly sort padded numbers, numbers preceding text, dates, floats, etc.](https://github.com/overset/javascript-natural-sort)

* [Browser.js: A Browser detector](https://github.com/ded/bowser)

* [Categorizr.js: A Device detector](https://github.com/Skookum/categorizr.js)

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

* [jQuery.stickysectionheaders: When scrolling down, always the current section heading "sticks" to the top](https://github.com/polarblau/stickySectionHeaders)

* [SlickGrid is an advanced JavaScript grid/spreadsheet component](https://github.com/mleibman/SlickGrid)

* [JustGage is a handy JavaScript plugin for generating and animating nice & clean gauges](http://justgage.com/)

* [Slick Carousel: the last carousel you'll ever need](http://kenwheeler.github.io/slick/)

* [Opentip: is a javascript tooltip framework](https://github.com/enyo/opentip)

* [Toolbar.Js: Toolbar allows you to quickly create tooltip style toolbars](https://github.com/paulkinzett/toolbar)

* [Fixed-sticky: A CSS position:sticky polyfill](https://github.com/filamentgroup/fixed-sticky)

* [fixto: A jQuery plugin for sticky positioning](https://github.com/bbarakaci/fixto)

* [Custom select boxes: Chosen is a jQuery plugin that makes long, unwieldy select boxes much more user-friendly](http://harvesthq.github.io/chosen/)

* [Quicksand: Reorder and filter items with a nice shuffling animation](https://github.com/razorjack/quicksand/)

## AngularJS
* [Angular Modules](http://ngmodules.org/)

* [AngularUI Router: he de-facto solution to flexible routing with nested views](https://github.com/angular-ui/ui-router)

* [ngCordova: Set of AngularJS extensions on top of the Cordova API](http://ngcordova.com/)

* [ui-calendar directive: A complete AngularJS directive for the Arshaw FullCalendar](https://github.com/angular-ui/ui-calendar)

* [sticky-headers: An AngularJS directive for making headers that won't scroll past the top of the screen](https://github.com/FutureStateMobile/sticky-header)

* [angular-chosen](https://github.com/localytics/angular-chosen)
