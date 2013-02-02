# eventie - event binding helper

Supported by IE8+ and good browsers.

``` js
var elem = document.getElementById('#id');
function onElemClick( event ) {
  console.log( event.type + ' just happened' );
}

eventie.bind( elem, 'click', onElemClick );

eventie.unbind( elem, 'click', onElemClick );
```

## Bower

eventie is [Bower](https://github.com/twitter/bower) compatible

``` bash
bower install desandro/eventie
```
