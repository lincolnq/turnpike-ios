## Turnpike for iOS

Turnpike enables deeplinking in iOS apps.

See the [turnpike-ios](http://urxtech.github.io/turnpike-ios/) homepage for documentation and installation instructions.

Visit the [turnpike-ios-discuss](https://groups.google.com/forum/#!forum/turnpike-ios-discuss) google group or join the conversation at [turnpike-ios-discuss@googlegroups.com](mailto:turnpike-ios-discuss@googlegroups.com)



### Easy Installation

[Cocoapods](http://beta.cocoapods.org/) is an Objective-C library manager. It makes installing Turnpike as easy as adding one line of code to a Podfile.

To install Cocoapods: 
<br>
$ [sudo] gem install cocoapods
<br>
$ pod setup

Then, to install Turnpike with Cocoapods:
<br>
1. Create a Podfile
2. <br>
2. Add the following to the Podfile:
3. <br>
platform :ios
<br>
pod 'Turnpike', '0.0.1'
<br>
3. Navigate to the directory containing the Podfile in terminal and issue the following command:
4. <br>
pod install

That's it! For a more thorough tutorial on Cocoapods, see: http://www.raywenderlich.com/12139.
