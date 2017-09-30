# node-qr-generate

> QR code generate using node.js

## Running Locally

```bash
$ git clone https://github.com/Rjoydip/node-qr-generate.git # or clone your own fork
$ cd node-qr-generate
$ npm install
$ npm start
```

Your app should now be running on [localhost:3000](http://localhost:3000).

## Server API

### `app.get('/');`

Render index.html

### `app.get('/qr');`

#### `Response:`

* 200: Success. Payload: url image(.png) base64 encoded object.

* 400: Error. Payload: error object.

Generate origin qr code as `image`.

***Note***
> The response of `/qr` url is a image(.png) base64 encoded data not canvas element or string data.
