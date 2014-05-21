Flex Widget: Playlist List Peel
=============

![Playlist List Peel Preview](http://www.beatbrokerz.com/flex/widget/fwlistpeel/preview.png)

This is a HTML5 playlist widget that allows you to flip through the beats in the playlist like they were a stack of polaroid snapshots. Just drag the top one off to get to the ones underneath!

* [**LIVE DEMO** (jsfiddle.net)](http://jsfiddle.net/beatbrokerz/X3eY7/)

### Pre-requisites

This widget requires a [flex app](http://www.beatbrokerz.com/flex) to be installed to your webpage in order for it to do anything useful. Refer to the [flex installation guide](http://www.beatbrokerz.com/flex/start) for more information on how to set up your own music app.

Once you have a flex app installed on your page, follow these steps to use this widget:

### Autoload Usage

This widget can be auto-loaded from the Beat Brokerz CDN. Use the following url in your autoload settings:

```
//www.beatbrokerz.com/flex/widget/fwlistpeel/widget.js
```

> You can use the [widget autoloader](http://www.beatbrokerz.com/flex/start/settings#autoloader) feature in your flex app settings (on Beat Brokerz) to autoload this widget automatically on every page your flex app is installed to.
>
> Or you can autoload it selectively on your pages using javascript:
> ```javascript
> flexloader.autoload('//www.beatbrokerz.com/flex/widget/fwlistpeel/widget.js');
> ```

### Widget Files / Controlled Loading

If you want to load this widget from your own server or you want to explicitly control the resources that get loaded on your page, you'll need to do the following:

1. Download the widget package [.zip file](https://github.com/beatbrokerz/flex-fwlistpeel/archive/master.zip)
2. Extract the contents and upload the files/folders to a public location on your webserver.

* fwlistpeel/widget.js (autoload ready)
* fwlistpeel/widget.css
* fwlistpeel/js/draggabilly.pkgd.min.js
* fwlistpeel/js/elastiStack.js

If you choose not to autoload, then you'll need to manually reference the required resources in your page like so:

> ```html
> <script type="text/javascript" src="/path/to/fwlistpeel/widget.js"></script>
> <script type="text/javascript" src="/path/to/fwlistpeel/js/draggabilly.pkgd.min.js"></script>
> <script type="text/javascript" src="/path/to/fwlistpeel/js/elastiStack.js"></script>
> <link rel="stylesheet" type="text/css" href="/path/to/fwlistpeel/widget.css" />
> ```

### Usage Instructions

Once the widget is loaded on your page, display the widget where you want using any of the standard [widget display methods](http://www.beatbrokerz.com/flex/widgets#display-methods). 

> **Embed Example:** 
> ```html
> <div data-bbflex="widget:fwlistpeel,size:large"></div>
> ```

### Widget Settings

The widget supports the following settings:

1. **size**: Optional. A string value ('small', 'medium', or 'large') which controls the size of the widget. Default: 'large'
2. **theme**: Optional. A string value which allows you to define a custom [theme prefix](http://www.beatbrokerz.com/flex/widgets/theming) for the widget
 
### Theme & Structure Reference

The rendered widget uses the following template structure and css classing.

```html

```
