# Sticky Header

A simple jQuery plugin to handle a sticky header that appears after you scroll a bit.

Check out a [demo](http://freshyill.github.io/Sticky-Header/).

## How it works

    $(document).ready( function() {
      $('.element').stickyHeader(options);
    });

## Using Options

    $(document).ready( function() {
      $('.element').stickyHeader({
        triggerElement: 'element',
        hiddenClass: 'class',
        scrollOffset: number,
        scrollInterval: number
      });
    });

## Options

### `triggerElement`

The element that triggers the sticky header to appear when it exits the top of the viewport. Default is `.contentbody` but you probably want to change it.

### `hiddenClass`

Class that will be added/removed to/from your sticky header. Default is `is-hidden`,

### `scrollOffset`

Specify an integer. Negative values will delay the appearance of the sticky header relative to the trigger element. Positive values will make it appear sooner. Default is `null`.

### `scrollInterval`

How often to check for scroll activity, measured in milliseconds. Higher values will let you delay appearance of the sticky header. Lower values will kill performance. Default is `250`.



## Todo

* Standard Github stuff like a demo, bower.json, etc.
