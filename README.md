[![electronify](http://i.imgur.com/q2L4Qna.png)](#)

# Electronify [![Support this project][donate-now]][paypal-donations]

The simplest way to build Electron apps.

[Electron](https://github.com/atom/electron) is amazing! Electronify makes its usage simpler by reusing the same code snippets in common apps.

[![electronify](http://i.imgur.com/o5sBv1w.png)](#)

## Installation

```sh
$ npm i -g electronify
```

## Example

```js
// Dependencies
var Electronify = require("electronify");

// Create the app
var app = Electronify(__dirname + "/app/index.html", {
    resizable: false
});
```

## Documentation

### `Electronify(path, options)`
Creates a new browser window based on Electron.

#### Params
- **String** `path`: The path to the HTML file.
- **Object** `options`: An object representing the browser window options. It has the following defaults:
 - `width` (Number): The window width (default: `800`).
 - `height` (Number): The window height (default: `600`).

#### Return
- **ElectronApp** The Electron app object extended with the following fields:
 - `mainWindow` (BrowserWindow): The browser window that was created.

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

## License

[KINDLY][license] © [Ionică Bizău][website]

[license]: http://ionicabizau.github.io/kindly-license/?author=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica@gmail.com%3E&year=2015

[website]: http://ionicabizau.net
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md