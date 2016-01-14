css-js-helpers-libs
===================

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C2HFZWSUPV47Q" target="_blank">
  <img src="https://raw.githubusercontent.com/Blah2014/phonegap-inmobi-plugin/gh-pages/images/BuymeaCoffee.png" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!" />
</a>

List of css, js libs and frameworks

## MAC
* AMPPS (if port 80 is busy)
```java
$ sudo apachectl stop
```

## Install RubyGem on Windows to use Hologram
```html
Go to: http://rubyinstaller.org/downloads/
Install latest Ruby
Note: When installing Ruby make sure to check add PATH
Download latest DevKit
Create folder under C: C:\RubyDevKit and extract DivKit into
run: cd C:\RubyDevKit
run: ruby dk.rb init
Note: this will create config.yml
Open config.yml
Uncomment line:11 and modify to - C:/Ruby22-x64
run: ruby dk.rb install

Now you can use Hologram to generate styleguide for your CSS and JavaScript
```

## CSS, JavaScript and PHP code documentation Gen.
* [JSDOC: An API documentation generator for JavaScript](https://github.com/jsdoc3/jsdoc)

* [JSDOC - Minami: A clean, responsive documentation template theme for JSDoc 3](https://github.com/Nijikokun/minami)

* [Hologram: CSS beautiful style guide generator](https://github.com/trulia/hologram)

* [Hologram - Cortana : a sexy Hologram theme](https://github.com/Yago/Cortana)

* [Hologram - Hologram Github Theme](https://github.com/wearecube/hologram-github-theme)

## Cocos2d-JS
* [Cocos2d-JS: Online API Documentation](http://www.cocos2d-x.org/reference/html5-js/V3.7/index.html)

* [Cocos2d-JS: Online Reference Documentation](http://www.cocos2d-x.org/reference/native-cpp/V3.6/index.html)

* [Cocos2d-JS: GitHub](https://github.com/cocos2d/cocos2d-js)

* [Cocos2d-JS: TUTORIALS](http://cocos2d-x.org/docs/tutorial/framework/html5/en)

* [1) Virtual Controls Overlay: Joystick and Button](https://supportforums.blackberry.com/t5/tkb/articleprintpage/tkb-id/browser_dev@tkb/article-id/142)

* [2) GitHub: Virtual Controls Overlay: Joystick and Button](https://github.com/oros/ControlsOverlay.js)

* [Freewill.js (Web Only): There are six (6) controls in total](https://github.com/oros/Freewill.js/blob/master/Freewill.js)

* [AppWarp: Multiplayer games solution](http://appwarp.shephertz.com/)

* [SonarLearning](http://www.sonarlearning.co.uk/topicpage.php?topic=game)

* [CocosLearning](http://cocos.sonarlearning.co.uk/docs)

* [Cocos Studio: tutorials](https://github.com/chukong/cocos-docs/tree/master/tutorial/studio)

* [EasyStar.js: asynchronous pathfinding in javascript](https://github.com/prettymuchbryce/easystarjs)

* [PathFinding.js: A comprehensive path-finding library in javascript](https://github.com/qiao/PathFinding.js)

## Desktop apps with web technologies
* [ELECTRON: Build cross platform desktop apps with web technologies](http://electron.atom.io/)

## JS: Fast image filters
* [WebGLImageFilter: ](Fast image filters for Browsers with WebGL support)

* [jsfeat: The project aim is to explore JS/HTML5 possibilities using modern & state-of-art computer vision algorithms](https://github.com/inspirit/jsfeat)

## Game Resources
* [Game Mechanic Explorer](http://gamemechanicexplorer.com/)
* [visibility-polygon-js: This library can be used to construct a visibility polygon for a set of line segments](https://github.com/byronknoll/visibility-polygon-js)
* [(WEB)SIGHT & LIGHT: how to create 2D visibility/shadow effects for your game](http://ncase.me/sight-and-light/)
* [(GitHub)SIGHT & LIGHT: how to create 2D visibility/shadow effects for your game](https://github.com/ncase/sight-and-light)
* [2d Visibility: Ray casting](http://www.redblobgames.com/articles/visibility/)
* [js-intersections: A JS utility class used to find intersections between any combination of lines, circles, ellipses, polylines, polygons, rectangles, quadratic beziers, and cubic beziers](https://github.com/thelonious/js-intersections)
* [js-intersections: Docs](http://www.kevlindev.com/gui/math/intersection/)
* [kld-intersections](A library of intersection algorithms covering all SVG shape types)

## Extras
* [The definitive front-end performance guide](http://browserdiet.com/en/)

* [TinyMCE: WYSIWYG editor](http://www.tinymce.com/)

* [Fast-Paced Multiplayer: A series of articles explaining the architecture of a fast-paced client-server multiplayer game](http://www.gabrielgambetta.com/fpm1.html)

* [Real Time Multiplayer in HTML5](http://buildnewgames.com/real-time-multiplayer/)

* [A Snowball Fight written with HTML5/WebSockets](https://github.com/hikirsch/NodeGame-SnowballFight)

* [APE (Ajax Push Engine)](http://ape-project.org/)

* [7 Habits of Highly Effective Media Queries](http://bradfrost.com/blog/post/7-habits-of-highly-effective-media-queries/)

* [PLACEHOLD.IT: A quick and simple image placeholder service](http://placehold.it/)
```java
// PLACEHOLD.IT Example
http://placehold.it/136x136/09f/fff.png&text=136x136
```

* [Online bitmap font generator](http://kvazars.com/littera/)

* [Tournament Bracket Generator](https://gist.github.com/sterlingwes/4199115)

* [jQuery Bracket library](http://www.aropupu.fi/bracket/)

* [JQUERY.GRACKET.JS: A JQuery/Canvas approach to creating single elimination tournament brackets](http://erik5388.github.io/jquery.gracket.js/)

* [jTournament: Makes jQuery make tournament trees using canvas](https://github.com/nicwest/jTournament)

* [jQuery Mouse Wheel Plugin](https://github.com/jquery/jquery-mousewheel)
```java
// jQuery Smooth Mouse Wheel Scrolling
var page = $('body'),
    scrollRange = 60,
    scrollSpeed = 200;

$(window).mousewheel(function(event, delta, deltaX, deltaY) {
    if (delta < 0) {
        page.stop(true,true).animate({scrollTop: page.scrollTop()+scrollRange}, scrollSpeed);
    } else if (delta > 0) {
        page.stop(true,true).animate({scrollTop: page.scrollTop()-scrollRange}, scrollSpeed);
    }
    return false;
});
```

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

* [Simple Styles for &lt;hr&gt;'s](https://css-tricks.com/examples/hrs/)

* [Convert image to base64](http://www.base64-image.de/)

* [Load Awesome: An awesome collection of Loaders and Spinners](https://github.com/danielcardoso/Load-Awesome)

* [Hover.css: A collection of CSS3 powered hover effects](http://ianlunn.github.io/Hover/)

* [Apple TV Parallax](https://github.com/balajmarius/Apple-TV-Parallax)

* [Bootstrap.css](http://getbootstrap.com/css/)

* [Bootstrap-select: Bootstrap using button dropdown](https://silviomoreto.github.io/bootstrap-select/)

##### Yahoo Finance API
```javascript
// Get
http://chartapi.finance.yahoo.com/instrument/1.0/aapl/chartdata;type=quote;range=1d/json
// You can use: json, csv or xml
```

##### PHP

* [PHP Simple HTML DOM Parser](http://simplehtmldom.sourceforge.net/)

* [HTTPFUL: focus on interacting with APIs instead of sifting through curl set_opt pages and is an ideal PHP REST client](https://github.com/nategood/httpful)

* [Slim: PHP micro framework that helps you quickly write simple yet powerful web applications and APIs](http://www.slimframework.com/)

* [PHP client for Yahoo Finance API](https://github.com/scheb/yahoo-finance-api)

* [CodeIgniter is a powerful PHP framework with a very small footprint](http://www.codeigniter.com/)

* [CodeIgniter: plugins](https://github.com/bcit-ci/CodeIgniter/wiki/_pages)

* [CodeIgniter: Ion Auth Lightweight Auth System](https://github.com/benedmunds/CodeIgniter-Ion-Auth)

* [CodeIgniter Rest Server](https://github.com/chriskacerguis/codeigniter-restserver)

* [Elephant.io: provides a socket.io client fully written in PHP](https://github.com/Wisembly/elephant.io)

##### PHP OAuth 2.0 Client - Provider Client Libraries
* [OAuth 2.0 Client list](https://github.com/thephpleague/oauth2-client/blob/master/README.PROVIDERS.md)
* [Google Provider for OAuth 2.0 Client](https://github.com/thephpleague/oauth2-google)

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

* [SlickMap CSS](https://github.com/rizkysyazuli/SlickMap-CSS)

## Javascript
* [HeadJS: Async files loader](http://headjs.com/)

* [Headroom.js: Hide your header until you need it](https://github.com/WickyNilliams/headroom.js)

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

* [Parallaxify: add depth to your project](https://github.com/hwthorn/parallaxify)

* [ScrollMagic: helps you to easily react to the user's current scroll position](https://github.com/janpaepke/ScrollMagic/)

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

* [Accounting.js: Simple and advanced number, money and currency formatting](https://github.com/openexchangerates/accounting.js)

```javascript
// Add a thousands separator
// Example: 1000 will be 1,000
number.toString().replace(/(\d)(?=(\d{3})+(?!\d))/g, '$1,')
```

* [XDate: A Modern JavaScript Date Library](http://arshaw.com/xdate/)

* [Fullcalendar.io: A JavaScript event calendar. Customizable and open source](http://fullcalendar.io/)

* [Video.js: The open source HTML5 video player](http://www.videojs.com/)

* [PhotoSwipe: IMAGE GALLERY FOR MOBILE AND TOUCH DEVICES](http://photoswipe.com/)

* [Swiper: is the free and most modern mobile touch slider with hardware accelerated transitions and amazing native behavior](https://github.com/nolimits4web/Swiper)

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

* [Chart.js: Simple HTML5 Charts](https://github.com/nnnick/Chart.js)

* [Chart.js: Legend plugin](https://github.com/bebraw/Chart.js.legend)

* [Fabric.js: is a powerful and simple Javascript HTML5 canvas library](http://fabricjs.com/)

* [amCharts is an advanced charting library](https://www.amcharts.com/)

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

* [Sticky-Kit: A jQuery plugin for making smart sticky elements](https://github.com/leafo/sticky-kit)

* [Custom select boxes: Chosen is a jQuery plugin that makes long, unwieldy select boxes much more user-friendly](http://harvesthq.github.io/chosen/)

* [Quicksand: Reorder and filter items with a nice shuffling animation](https://github.com/razorjack/quicksand/)

* [Lazy Load Plugin for jQuery](https://github.com/tuupola/jquery_lazyload)

* [Lazy Load XT jQuery plugin: Lazy load XT is a jQuery plugin for images, videos and other media](https://github.com/ressio/lazy-load-xt/)

* [DropdownCheckList: Dropdown checklist jQuery widget](http://sourceforge.net/projects/dropdownchecklist/)

* [Smart App Banner](https://github.com/kudago/smart-app-banner)

* [tableExport.jquery.plugin: JSON, XML, PNG, CSV, TXT, SQL, MS-Word, Ms-Excel, Ms-Powerpoint, PDF](https://github.com/hhurz/tableExport.jquery.plugin)

## AngularJS
* [Angular Modules](http://ngmodules.org/)

* [AngularUI Router: he de-facto solution to flexible routing with nested views](https://github.com/angular-ui/ui-router)

* [ngCordova: Set of AngularJS extensions on top of the Cordova API](http://ngcordova.com/)

* [ui-calendar directive: A complete AngularJS directive for the Arshaw FullCalendar](https://github.com/angular-ui/ui-calendar)

* [sticky-headers: An AngularJS directive for making headers that won't scroll past the top of the screen](https://github.com/FutureStateMobile/sticky-header)

* [angular-chosen](https://github.com/localytics/angular-chosen)

* [angular-socket-io: Socket.IO component for AngularJS](https://github.com/btford/angular-socket-io)

* [reCaptcha](https://github.com/VividCortex/angular-recaptcha)

* [Satellizer: built-in support for Google, Facebook, LinkedIn, Twitter, Instagram, GitHub, Bitbucket, Yahoo, Twitch, Microsoft (Windows Live) OAuth providers](https://github.com/sahat/satellizer)

* [angular-export-table: : JSON, XML, PNG, CSV, TXT, SQL, MS-Word, Ms-Excel, Ms-Powerpoint, PDF](https://github.com/Epotignano/angular-export-table)
