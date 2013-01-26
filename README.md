imagepreloader
==============

The same file works in both places.

In Node
-------

You can either 

    var Preload = require('imagepreloader');
    var Image = require('canvas').Image;
    var preload = new Preload({Image:Image});

Or,

In your browser
---------------
    
    <script src='index.js'></script>
    <script>
        var Preload = new Preload;
    </script>

Where index.js is the file found in this directory. 


How To Use
==========

Just open your browser to 

    example/browser/index.html

Or cd /example/node and run 

    node test.js
