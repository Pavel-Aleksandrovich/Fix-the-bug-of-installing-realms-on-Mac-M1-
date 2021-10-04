# Fix-the-bug-of-installing-realms-on-Mac-M1
The best solution to fix the bug of installing realms on the Mac M1

https://github.com/CocoaPods/CocoaPods/issues/9907

open a terminal

go to the root directory of your app

sudo arch -x86_64 gem install ffi

pod init

nano podfile

arch -x86_64 pod install
