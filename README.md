Open External Links in New Window
=================================

JavaScript snippet for Chromeless Apps
--------------------------------------

Automatically open external links in a new window when your web app runs in a chromeless runtime.

Especially useful for [Firefox OS](http://www.mozilla.org/en-US/firefox/os/) and [iOS](http://developer.apple.com/library/ios/#documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html) web apps! Created for Firefox OS apps, works on the whole modern web.

### Why it doesn't suck

 - Event delegation: Fast load and works on dynamic content
 - Doesn't use `window.open`, just changes the `target` for clicked links
 - Keeps existing `target` references intact
 - Vanilla JavaScript (i.e. no dependencies), the best cross-browser framework!

### How to Use

Either or:

 - Copy code into your web app project,
 - Embed deferred via github,
 - … or just get inspired and make your own.
