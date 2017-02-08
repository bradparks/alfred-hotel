# alfred-hotel

[![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

> [Alfred 3](https://www.alfredapp.com/) workflow that lets you start, stop and open [Hotel](https://github.com/typicode/hotel) apps

![alfred hotel workflow screenshot in action](screenshot.png)


## Requirements

- [Node.js](https://nodejs.org) >= 4.x
- [Hotel](https://github.com/typicode/hotel)
- Alfred [Powerpack](https://www.alfredapp.com/powerpack/)


## Install

```shell
$ npm install -g alfred-hotel
```


## Usage

In Alfred, type `hotel` to list all [Hotel](https://github.com/typicode/hotel) apps, press <kbd>Space</kbd> to search through list.

With selected app you can:

- <kbd>Enter</kbd> to start and open app in default browser (http://example.dev)
- <kbd>Alt</kbd> + <kbd>Enter</kbd> to open app without local domain (http://127.0.0.1:50409)
- <kbd>Command</kbd> + <kbd>Enter</kbd> to stop selected app
- <kbd>Ctrl</kbd> + <kbd>Enter</kbd> to open app folder
- <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy app url
- <kbd>Shift</kbd> to preview url with quicklook


## Settings

By default workflow works with following Hotel settings:

- Hotel is available at `http://localhost:2000`
- Local domains are in `.dev` zone

You can change this in [`Configure workflow and variables`](screenshot-settings.png).


## Related

- [alfy](https://github.com/sindresorhus/alfy) - Create Alfred workflows with ease
- [hotel](https://github.com/typicode/hotel) - A simple process manager for developers


## License

MIT © [John Grishin](http://johngrish.in)
