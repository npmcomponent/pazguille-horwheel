*This repository is a mirror of the [component](http://component.io) module [pazguille/horwheel](http://github.com/pazguille/horwheel). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/pazguille-horwheel`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Horwheel

Scroll horizontally with mouse wheel.

It's cross-browser compatible:
- Chrome (OS X, Windows)
- Firefox (OS X, Windows)
- Opera (OS X, Windows)
- Safari (OS X, Windows)
- IE9
- IE8
- IE7

## Installation

	$ component install pazguille/horwheel

See: [https://github.com/component/component](https://github.com/component/component)

## How-to
First, require horwheel:
```js
var horwheel = require('horwheel');
```

Then, define your wrapper:
```js
var wrapper = document.querySelector('#wrapper');
```

Finally, execute horwheel function with wrapper parameter:
```js
horwheel(wrapper);
```

### Standalone
Also, you can use it without components.
First, add standalone file:
```html
<script src="../standalone/horwheel.js"></script>
```

Then, define your wrapper:
```js
var wrapper = document.querySelector('#wrapper');
```

Finally, execute horwheel function with wrapper parameter:
```js
horwheel(wrapper);
```

## Contact
- Guille Paz (Frontend developer - JavaScript developer | Web standards lover)
- E-mail: [guille87paz@gmail.com](mailto:guille87paz@gmail.com)
- Twitter: [@pazguille](http://twitter.com/pazguille)
- Web: [http://pazguille.me](http://pazguille.me)

## License
### The MIT License
Copyright (c) 2013 [@pazguille](http://twitter.com/pazguille)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
