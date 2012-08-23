Quake Framework
=================

Quake Framework utilizes some of the best frameowrks available today, seamlessly integrating them together to create a feature-rich compilation framework to kickstart your projects for extreme rapid development.

Please note that this is a framework and **not** a website system. All included libraries and frameworks are almost completely unconfigured default versions, with the exception of what was required for integration.

Quake Framework uses CodeIgniter for back end development, and a combination of Twitter Bootstrap (responsive version using LESS, with Font Awesome already configured for icons), HTML5 Boilerplate, jQuery and jQuery UI for the front end. It also sports Bootstrap themes for jQuery UI and tinyMCE for consistency, and Modernizr for better cross-browser compatibility (Modernizr and HTML5 Boilerplate are implemented via Initializr and already configured). TinyMCE is preconfigured to utilize the main stylesheet, and also has the CodeMagic plugin installed, which uses CodeMirror so that the tinyMCE HTML editor has syntax highlighting and code hinting, as well as preservation for code indentation. Highstocks is also included for charting/graphing data.



What's Inside
-------------

As of version 0.1.2, included libraries/frameworks are:

+ **Initializr 3.0 (responsive)** - http://www.initializr.com/
+ **Modernizr 2.6.1** - http://modernizr.com/
+ **jQuery 1.8.0** - http://jquery.com/
+ **jQuery UI 1.8.23 (with ALL plugins)** - http://jqueryui.com/
+ **jQuery TotalStorage** - https://github.com/jarednova/jquery-total-storage - (Plugin for local storage)
+ **jQuery Cookie** - https://github.com/carhartl/jquery-cookie - (Total Storage falls back on this in browsers that don't support local storage)
+ **Bootstrap theme for jQuery UI 0.23** - http://addyosmani.github.com/jquery-ui-bootstrap/
+ **Codeigniter 2.1.2** - http://codeigniter.com/
+ **Twitter Bootstrap 2.1.0** - http://twitter.github.com/bootstrap/
+ **HTML5 Boilerplate 3.0.3** - http://html5boilerplate.com/ - (as included with Initializr)
+ **Highstock 1.1.6** - http://www.highcharts.com/
+ **LESS 1.3.0** - http://lesscss.org/ - (as included with Twitter Bootstrap)
+ **Font Awesome 2.0.0** - http://fortawesome.github.com/Font-Awesome/
+ **tinymce 3.5.6 (jQuery edition)** - http://www.tinymce.com/
+ **Cirkuit 0.5** - http://www.cirkuit.net/projects/tinymce/cirkuitSkin/ (Boostrap-like theme for tinyMCE)
+ **CodeMirror 2.32** - http://codemirror.net/
+ **Codemagic** - http://codemagic.sutulustus.com/
+ **Google Prettify (June 2011)** - http://code.google.com/p/google-code-prettify/ - (as included with Twitter Bootstrap)
+ **GlyphIcons 1.6** - http://glyphicons.com/ - (as included with Twitter Bootstrap)
+ **FamFamFam Silk Icons 1.3** - http://www.famfamfam.com/ - (as included with Cirkuit)



Notes
-----

+ All default source files for all of the above are located in the `/sources` directory.
+ All of the above listed frameworks and libraries are already set up, integrated and configured to work together seamlessly!
+ LESS is currently configured to be compiled with an application such as "Crunch!" - see LESS documentation for use with less.js



Quick start
-----------

Clone the repo, `git clone git://github.com/clowerweb/Quake-Framework.git`.



Versioning
----------

Quake Framework will be released under the Semantic Versioning guidelines, using the following format:

`[major].[minor].[patch]`

For more information on Semantic Versioning, visit http://semver.org/.



Bug tracker
-----------

If you find a bug, please report it in the github repo issue tracker. Thanks!

https://github.com/clowerweb/Quake-Framework/issues



Authors
-------

**Chris Clower**

+ http://clowerweb.com/
+ http://twitter.com/clowerweb
+ http://github.com/clowerweb
+ chris@clowerweb.com or clowerweb@fullsail.edu



Copyright and license
---------------------

Quake framework is currently in the process of seeking an appropriate license. Until then, it is being released as public domain, but this is subject to change without notice in future releases.

Please see the `/licenses` folder for licenses of works used, where applicable. Note that this list may be incomplete.