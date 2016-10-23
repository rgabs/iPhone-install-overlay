### What is it?

A JavaScript plugin which shows a message to install the web application on iPhone devices(on Safari browser). This will be useful if you are building a progressive web application. If you don't know what progressive web applications are, head over to [Progressive web apps blog by Google](https://developers.google.com/web/progressive-web-apps/)

<br/>

### [Blog/Documentation about how to use the plugin](http://rahulgaba.com/front-end/2016/07/31/Showing-add-to-homescreen-banner-in-iPhone-Safari.html)
<br/>

### Why is it required

Though service workers are not yet supported on Safari, we can still achieve a lot using HTML5 application cache and localStorage. And Safari does support launching your application in a full screen mode using just a meta-tag. (Refer [Safari meta-tags](https://developer.apple.com/library/iad/documentation/AppleApplications/Reference/SafariHTMLRef/Articles/MetaTags.html) to know more).

This is a feature chrome has recently released where it checks that if your web app is using service workers and shows a banner to install the application to the home screen. [Official blog by Google](https://developers.google.com/web/updates/2015/03/increasing-engagement-with-app-install-banners-in-chrome-for-android?hl=en)

#### I believe that this is a really cool feature to have and I thought of bringing the same feature to the iOS devices.

<br/>

### Screenshots and Demo
Working demo of the plugin: [http://rahulgaba.com/iPhone-install-overlay](http://rahulgaba.com/iPhone-install-overlay)
![Full GIF](/src/images/app.gif "Full GIF")
