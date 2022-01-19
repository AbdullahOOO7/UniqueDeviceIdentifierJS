# UniqueDeviceIdentifierJS

~ It's an iOS framework which provide unique identifier of device.

## UniqueDeviceIdentifierJS version # 1.0.0

## Description:

~ This framework will provide device unique identifier so you can judge whether has previous device or new one or might be he/she deleted the app and installing again. This framework can help you to identify uniqueness of user while registration.


## How to integrate this to project:
~ Steps to perform :-

1 - Goto Xcode 

2 - Right click on your project name

3 - Select Add Packages

4 - Select Github option or simply add below package URL in search bar

5 - https://github.com/AbdullahOOO7/UniqueDeviceIdentifierJS

6 - Click on Add Package, WWoooaaa!!! package successfully added to your project


## How to integrate this to other framework as a dependency:

~ Simply you can perform above steps to add this framework as a dependency in other frameworks

## How to share this framework directly with other developers:

~ On github there is source folder in which UniqueDeviceIdentifierJS.xcframework file is added which can be shared directly with other devs to use the functionality of this framework.

## How to use this framework in project:

import UniqueDeviceIdentifierJS

let manager = IdentifierManager()

print(manager.getDeviceID())

## About framework stability and uniqueness 

■ Does it remain the same after application reinstalling? If it’s possible, implement it, if not – describe why.
■ If your library is used in two different applications, will the ID that your library provides be the same inside of these two apps?

Answer is below for above questions

Early iOS releases gave every device a unique identifier, but this was soon abused by developers to identify individual users uniquely – something that Apple really dislikes. So, Apple removed the truly unique identifier and instead introduced an identifier for each vendor: a UUID that's the same for all apps for a given developer for each user, but varies between developers and between devices. That is, if a user has five of your apps installed and five of mine, your five will all share the same vendor identifier.

Cheers 🥂 🍻 🍺  Enjoy



