element-mixpanel
============
Web Component for retrieving data from mixpanel.

## Getting Started

## Contributing
1. Clone repo
2. `npm install`
3. `bower install`

Note: dependencies are installed into parent directory.

## Testing

Run a static http server in the parent directory:

```sh
python -m SimpleHTTPServer
```

Or other method using NodeJS:

```sh
http-server ./
```

This starts a web server on port 8000, so you can test your new element by navigating a browser to `localhost:8000/element-mixpanel/test/index.html`.

### web-component-tester

The tests are also compatible with [web-component-tester](https://github.com/Polymer/web-component-tester). You can run them on multiple local browsers via:

```sh
npm install -g web-component-tester
wct
```
