Contao jQuery selectBox
===================

Simple extension to provide the [MooTools FancySelect plugin](http://mootools.net/forge/p/fancyselect) in Contao.

## Styling

If you want to create your own styles without overriding the default one, create your own `moo_fancyselect` template and remove or disable the line `$GLOBALS['TL_CSS'][] = …` in the PHP section of the template.

## Configuration

In order to configure the default initialization, create your own `moo_fancyselect` template and change the script part. See the [documentation of the original plugin](http://mootools.net/forge/p/fancyselect) for all available options.