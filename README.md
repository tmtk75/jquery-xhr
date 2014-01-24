# node-jquery-xhr
Provide `window`, `jQuery` and `$` to node integrating `jquery`, `jsdom` and `xmlhttprequest`.

## How to use

Let's say you use npm, add "node-jquery-xhr" to dependencies section of package.js

    require("node-jquery-xhr")

You can access like this

    window.document
    body = $("body")

Also `$.ajax`, too.

    $.ajax({
      method: 'get',
      url: 'http://www.yahoo.com',
      success: function(r) {
        console.log(r);
      }
    });

## History
### 1.8.3
- use jquery 1.8.3 <https://github.com/coolaj86/node-jquery>

### 0.1.1  
- support $.ajax using xmlhttprequest

### 0.1.0  
- first release

## License
MIT License

## Thanks
- [git://github.com/coolaj86/node-jquery.git][node-jquery]
- [git://github.com/tmpvar/jsdom.git][jsdom]
- [git://github.com/driverdan/node-XMLHttpRequest.git][xhr]

[node-jquery]: https://github.com/coolaj86/node-jquery.git
[jsdom]: https://github.com/tmpvar/jsdom.git
[xhr]: https://github.com/driverdan/node-XMLHttpRequest.git
