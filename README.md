svg-to-html-polyfill
=================

Mirror for https://code.google.com/p/innersvg/ + some files to make the package available in [npm](https://www.npmjs.com/package/svg-to-html-polyfill) and bower.


Introduction
============

This JavaScript library that provides innerHTML, outerHTML properties on all SVGElements.

innerHTML and outerHTML in a SVG document works in Chrome 6+, Safari 5+, Firefox 4+ and IE9+.

innerHTML and outerHTML in a HTML5 document works in Chrome 7+, Firefox 4+ and IE9+.

Doesn't work in Opera since the SVGElement interface is not exposed.

Sample Code
===========

    <g id="foo"/>

    document.getElementId("foo").innerHTML = "<circle r='40' fill='green'/>";
    document.getElementId("foo").outerHTML = "<g id="foo"><circle r='40' fill='green'/></g>";


License
=======

Apache License, Version 2.0
