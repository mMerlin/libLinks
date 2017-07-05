# Chart.js Issue [4439](https://github.com/chartjs/Chart.js/issues/4439)

In Chart.js version 2.6.0 (and earlier), axis scaleLabel text is centered to the middle of graph body.  Longer label strings will truncate at the edge of the canvas.  Depending on the position of the graph in the canavs, either or both ends can be truncated.  When the graph is not centered in the canvas, better results can be obtained by adjusting the scaleLable text placement.

Change the scaleLabel text placment to adjust the string justification and origin when truncation would occur with the default center position.

[Problem demonstration](https://jsfiddle.net/microMerlin/3wfoL7jc/) with Chart.js version 2.6.0
[Fix demonstration](https://jsfiddle.net/microMerlin/9qLkwpqq/) using snapshot from branch issue-4439 of [Chart.js](https://github.com/mMerlin/Chart.js) fork.
[Pull Request](https://github.com/chartjs/Chart.js/pull/4463) Handle scaleLabel positioning when simple center would truncate
