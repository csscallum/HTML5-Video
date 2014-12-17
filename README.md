Responsive Bulletproof HTML5 Video
=======================

About
-----

Adapted from [csscallum](https://github.com/csscallum/HTML5-Video/)'s "Bulletproof HTML5 Video" with responsiveness added.

-   Be sure to change `.videoContainer { max-height: 1200px; }` and `.videoContainer video { max-width: 1920px; }` to the max-width and max-height of your video.

This solution only requires two video formats, MP4 and WebM, with a Flash fallback using the .mp4 file for older browsers that don't support HTML5 video.

### WebM & MP4

WebM is the standards based video format designed to provide a royalty-free, high-quality open video compression format for use with HTML5 video and is supported in *Chrome*, *Firefox* and *Opera*. *IE9* (and up) and Safari only supports the more commonly known MP4 video as do both *iOS* and *Android* devices.

Support
-------
Browser/device support include Internet Explorer, Firefox, Chrome, Safari, Opera, iOS, Android and the Blackberry Browser. The only dark area is in Opera Mini which does not support the Video element.

Demo
-----

[Can be viewed here](https://rawgithub.com/gnowland/HTML5-Video/master/index.html).