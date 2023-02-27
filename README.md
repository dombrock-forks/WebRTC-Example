# WebRTC Boilerplate
---

A simple WebRTC boilerplate.

Based on the example code written by [Shane Tully](https://github.com/shanet/WebRTC-Example).

![screenshot]('docs/screenshot.png')

## Usage

The signaling server uses Node.js and `ws` and can be started as such:

```
$ npm install
$ npm start
```

With the server running, open a recent version of Firefox, Chrome, or Safari and visit `https://localhost:8443`.

* Note the HTTPS! There is no redirect from HTTP to HTTPS.
* Some browsers or OSs may not allow the webcam to be used by multiple pages at once. You may need to use two different browsers or machines.

## TLS

Recent versions of Chrome require secure websockets for WebRTC. Thus, this example utilizes HTTPS. Included is a self-signed certificate that must be accepted in the browser for the example to work.

## Problems?

WebRTC is a rapidly evolving beast. Being an example that I don't check often, I rely on users for reports if something breaks. Issues and pull requests are greatly appreciated.


