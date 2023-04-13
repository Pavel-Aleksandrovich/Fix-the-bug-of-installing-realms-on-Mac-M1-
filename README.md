# Fix-the-bug-of-installing-realms-on-Mac-M1
The best solution to fix the bug of installing realms on the Mac M1

https://github.com/CocoaPods/CocoaPods/issues/9907

open a terminal

go to the root directory of your app and enter

sudo arch -x86_64 gem install ffi

pod init

nano podfile

arch -x86_64 pod install


///
ERROR: Could not automatically select an Xcode project. Specify one in your Podfile like so:

Solution:
target 'desertOfWealth' do
project '/Users/pavelmishanin/Desktop/wvswift/desertOfWealth.xcodeproj'
