# How to Develop iOS Apps on Linux

This repo demonstrates how to develop a React Native iOS app from Linux.

The approach we take is to make an iOS app configurable to use different React Native packagers, so that we can point it to a packager running on Linux.

This accompanies an article on the subject, [How to Develop iOS Apps on Linux using React Native](http://www.proreactnative.com/How-to-Develop-iOS-Apps-on-Linux-Using-React-Native/).

Please try it out and let me know how it goes!

Basically you build the native code with a mac one time on the ios device to be able to get it up and running, then develop and iterate on the actual app on the javascript side of things with a packager that is loading the new bundle on a port that the device is sitting there listening to
