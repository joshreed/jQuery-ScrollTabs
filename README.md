jQuery-ScrollTabs
=================

A JQuery highly configurable plugin to handle scrolling tabs horizontally when not enough space is available. This is great for navigation in context of responsive layouts. Additionally, there's nearly infinite ways to configure the appearance using your own CSS or the available Options and API calls for changing the contents on-the-fly!

Demo
----

View a live demo of jQuery-ScrollTabs in action!

http://joshreed.github.io/jQuery-ScrollTabs/

Install
-------

There are two installation options:
* Bower - `bower install jquery-scrolltabs`
* Download - Traditional download at http://joshreed.github.io/jQuery-ScrollTabs/

Usage
-----

At it's most basic:

```
$('#tabSet').scrollTabs();
```

And to show the options availble:

```
 $('#tabSet').scrollTabs({
    scroll_distance: 350,        // Pixel width for how far to scroll with each single-click
    scroll_duration: 350,        // Milliseconds for how long to animate the scroll
    left_arrow_size: 26,         // Width of the left arrow (if you choose to customize this)
    right_arrow_size: 26,        // Width of the right arrow (if you choose to customize this)
    click_callback: function(e){ 
      // This shows the default callback, which will redirect the page based
      // on the 'rel' attribute.
      var val = $(this).attr('rel');
      if(val){
        window.location.href = val;
      }
    }
  });
```

Documentation
-------------

For more information or detailed usage instructions, please refer to the link below.

http://joshreed.github.io/jQuery-ScrollTabs/documentation.html
