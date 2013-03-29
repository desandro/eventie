# eventie - event binding helper

Supported by IE8+ and good browsers.

``` js
var elem = document.querySelector('#my-elem');
function onElemClick( event ) {
  console.log( event.type + ' just happened on #' + event.target.id );
  // -> click just happened on #my-elem
}

eventie.bind( elem, 'click', onElemClick );

eventie.unbind( elem, 'click', onElemClick );
```

## Bower

eventie is [Bower](https://github.com/twitter/bower) compatible

``` bash
bower install desandro/eventie
```

## IE 8

eventie add support for `event.target` and [`.handleEvent` method](https://developer.mozilla.org/en-US/docs/DOM/EventListener#handleEvent(\)) for Internet Explorer 8.
