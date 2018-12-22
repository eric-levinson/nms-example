# NMS HLS Remux Example

Showing off how [node-media-server](https://www.npmjs.com/package/node-media-server) can be used with [hls.js](https://www.npmjs.com/package/hls.js/v/canary) and [ffmpeg](https://www.ffmpeg.org) for an easy HTML5 Live Streaming experience.

### How to deploy and use

* git clone https://github.com/eric-levinson/nms-example
* npm init
* In public/index.html change STREAM_NAME to what you want
* node app.js
* In OBS:
 Settings -> Stream
Stream Type : Custom Streaming Server
URL : rtmp://localhost/live
Stream key : STREAM_NAME **(change this to what you have in index.html)**
* navigate to http://localhost:3000/index.html
