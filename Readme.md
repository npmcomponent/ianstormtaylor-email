*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/email](http://github.com/ianstormtaylor/email). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-email`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# email

  Parse an email address into its components, based on [component/url](https://github.com/component/url).

## Installation

    $ component install ianstormtaylor/email

## Example
    
```js
var email = require('email');
email.parse('johnny+nospam@example.com');
```

```js
{
  local: 'johnny+nospam',
  name: 'johnny',
  filter: 'nospam',
  domain: 'example.com'
}
```

## API

### email.parse(string)
  Parse the given email `string`.

### email.hasFilter(string)
  Check if the given email `string` has a `+` filter.

## License

  MIT
