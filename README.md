This code repository aims at introducing some recommended practices and notions while developing web applications for STB browser based platforms;

Points to Consider:

* set-to-box devices typically have limited resources (CPU, RAM, storage) and when GPU is available, making use of WebGL and HTML canvas over HTML DOM is preferred, as it leads to increased performance and fluidity

* also on the subject of performance, the use of "vanilla" JavaScript over any Desktop Frameworks is preferred as a means to prevent additional processing to achieve the same end result

* included Web Browsers don't necessarily match in available capabilities as their Desktop counterparts, which means that working code on Desktop won't necessarily ensure working results on STB as well

* user navigation should consider spatial navigation, by focusing the desired element and using key press style interaction, rather than click/touch

* app development should follow SPA (Single Page Application) patterns

* app resolution required to be 1080p (Full HD)



Below are some community projects and websites aimed at addressing these issues:

Part I - Generic Development Guidelines

Either going for a traditional JavaScript/HTML/CSS solution from scratch or considering an already existing Web App implementation for the Desktop, the following resources should help in addressing the issues mentioned above:

* Single-Page Application
  * https://en.wikipedia.org/wiki/Single-page_application
  * https://muffingroup.com/youknowbetter/#start
  * https://github.com/SantiagoGdaR/vanilla-spa
* Spatial Navigation
  * https://github.com/luke-chang/js-spatial-navigation
* Input - T9 Keyboard
  * https://github.com/lassse/t9-keyboard-js
* Input - Virtual Keyboard
  * https://github.com/hodgef/simple-keyboard

Part II - Performance Oriented Development

The UMA platform is built on RDK (Reference Design Kit), which provides support for Lightning, an app development framework designed to address the issues mentioned above

This app framework is specifically set for TV based user interfaces, with both usability and performance as core features

* Lightning TV App Development
  * https://github.com/rdkcentral/Lightning
