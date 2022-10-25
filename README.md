# Object Detection with TensorFlow.js Benchmark

This is a small benchmark to see how fast the [coco-ssd](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd) runs on TensorFlow.js in the browser.
To run the benchmark visit https://nonocam.github.io/poc-tfjs-demo/.

## Bechmark Results

| Device | Average FPS | Poor Chart™️ <br> (= ~ 5 fps) |
|----|----|----|
| iPhone 13 (Safari) | 20 | ==== |
| Samsung Galaxy S21 (Chrome) | 14 - 18 | ==== |
| iPhone 11 (iOS 15.4.1, Safari) | 15 - 18 | ==== |
| iPhone 12 64 GB (iOS 15.1, Safari) | 12 - 14 | === |
| iPhone 12 64 GB (iOS 15.1, Chrome) | 12 - 14 | === |
| iPhone 12 Pro Max | 12 - 14 | === |
| iPad Mini 6 (Safari) | 14 | === |
| Pixel 4 | 11 | === |
| iPad Pro 10.5" (iOS 15.4.1, Safari) | 9 | == |
| Xiaomi Mi 8 | 5 - 7 | == |
| iPhone 6S (Safari) | 5 | = |
| Samsung Galaxy Tab A T510 | 2 - 4 | |
| | | &nbsp; |
| MacBook Pro 14 M1 Pro (Chrome) | 60 | ============ |
| MacBook Pro 13 M1 (Chrome) | 40 | ======== |
| MacBook Pro 14 M1 Pro (Safari) | 30 | ====== |
| MacBook Pro 13 M1 (Safari) | 14 - 20 | ==== |
| MacBook Pro 13 (2018, 2.7 GHz i7, Intel Iris Plus Graphics 655 1536 MB, Firefox) | 18 - 20 | ==== |

## Contribute

Please feel free to run the demo on your devices and upload your results to GitHub (via PR or as Issues) or send me a message via Twitter: https://twitter.com/_vsaw

## Known Issues

- Detection Boxes may have the wrong position for some devices (e.g. iPhone 11 in Portrait mode). As a simple workaround I suggest you try to change the orientation of your device if possible (e.g. use in Landscape mode).

## See also

- https://www.tensorflow.org/js
- https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd
- https://github.com/nihui/ncnn-webassembly-nanodet/ another benchmark running ncnn on Web Assembly