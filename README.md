#  Webgl-mark2

> Port of glmark2 in webgl. It is a benchmark of the webgl rendering engine in JS.

[![Linux Build][travis-image]][travis-url]
[![Test Coverage][coveralls-image]][coveralls-url]

## Credit to glmark2

The jellyfish example is inspired from the [glmark2 repository](https://github.com/glmark2/glmark2). 

## Install

The project should install for any version of node 0.12+ onwards. To install node on your environment, please check [this url](http://nodejs.org)
```bash
npm i
```

## Usage

```bash
npm start
```
This project should work with Firefox 49+ or Chrome 51+.

## Results

Configuration for reaching these numbers: GTX1080, i3, full screen resolution, on Firefox. In Firefox about:config, set the layout.frame_rate variable to 0, if you want to overcome the default 60 FPS limit of all browsers.

| Jellyfish Count      | 32            | 256   |
| -------------------- |:-------------:| -----:|
| FPS in WebGL         | 1236          | 408   |
| FPS in ThreeJS       | 1181          | 396   |
| FPS in AFrame        | 1056          | 390   |

We average the measures over 10 samples for each case.

For the original results, the google sheet can be found [here](https://docs.google.com/spreadsheets/d/1GqJlZ6SVADBbqpSV1Vjf81xyznYCBkYlWrbz_AfCdsU/edit#gid=83899543).

![Jellyfish interface](https://github.com/Edouard360/webgl-mark2/blob/master/public/data/assets/jellyfish.gif)

## License

This software is  maintained with love by [Inovia Team](https://inovia-team.com).
Made in San Francisco.

[MIT](http://vjpr.mit-license.org)

[npm-image]: https://img.shields.io/npm/v/live-xxx.svg
[npm-url]: https://npmjs.org/package/live-xxx
[travis-image]: https://img.shields.io/travis/live-js/live-xxx/master.svg
[travis-url]: https://travis-ci.org/live-js/live-xxx
[coveralls-image]: https://img.shields.io/coveralls/live-js/live-xxx/master.svg
[coveralls-url]: https://coveralls.io/r/live-js/live-xxx?branch=master

