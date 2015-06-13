# Haxor MaterializeCSS

This forked repository contains the SASS sources for UI elements that will be used in haxor demos.

# Build

The `sassc` compiler in `tools/` is used to compile the Materialize source into a CSS. It is much faster than the Ruby version.

# Usage

1 - Add to your page directory the `materialize/` folder.
2 - Add the following tags:
```
<head>
...
<link type="text/css" rel="stylesheet" href="path/to/materialize/css/materialize.css"  media="screen,projection"/>
</head>
```
and also
```
<body>
...
<script type="text/javascript" src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
<script type="text/javascript" src="path/to/materialize/js/materialize.js"></script>
</body>
```

This will make all Material Design classes available for usage.

# Documentation

For further understanding how to use this tool: http://materializecss.com/getting-started.html


