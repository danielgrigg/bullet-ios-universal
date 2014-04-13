# bullet-ios-universal

A makefile for building bullet for ios.

## Getting started

$ ./build.sh

Assuming you have SVN, xcodebuild etc it'll generate a 
universal static lib of both simulator (i386, x64) and iOS 
targets (armv7, armv7s and arm64) in ./vendor/ios/lib .

build.sh should give guidance if you want to integrate
the makefile in your own project.

## Improvements?

- simplify the makefile, less verbosity
- better dependency evaluation.  Right now we rely on the user running the bootstrap target.
- versioning
