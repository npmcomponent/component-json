*This repository is a mirror of the [component](http://component.io) module [component/json](http://github.com/component/json). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-json`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# json

  JSON parser / stringifier.

## Installation

    $ component install component/json

## Example

```js
var json = require('json');
json.parse('{"foo":"bar"}');
// => { foo: 'bar' }
```

## Fallback

  If you're working with browsers that do not provide a native `JSON`,
  then you should install [json-fallback](https://github.com/component/json-fallback)
  and this module will export that instead.

# License

  MIT


