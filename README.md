# libLinks

This repository is a convenient place to put and manage files that I need to be able to access from elsewhere on the Internet.

The initial driver for this was to be able to do live tests and demonstration of local changes to the
[Chart.js](https://github.com/mMerlin/Chart.js) library, without needing to store the generated distribution files in the
repository, and do a full commit, push cycle for every tweak during testing.  The updated library file can be put here instead,
then used as an external resource from jsfiddle.

[How to use a file in a github repository as a jsfiddle external resource](https://stackoverflow.com/questions/9841026/reference-github-file-in-jsfiddle)
* Go to the file on github
* click RAW
* copy the URL
* goto to [rawgit.com](http://rawgit.com/)
* paste the URL in the box
* copy the development URL
  * For `https://github.com/mMerlin/libLinks/blob/master/chartjs-issue-4439/Chart.bundle.js` that became `https://rawgit.com/mMerlin/libLinks/master/chartjs-issue-4439/Chart.bundle.js`
    * just replace the `https://github.` prefix with `https://rawgit.`, and remove `/blob` from the basic (not raw) url
* paste into the external resource on jsfiddle

The libLinks [repository home page on github.io](https://mmerlin.github.io/libLinks/index.html)
