# ARMusicRoom
 An AR app providing an assembly music room
 
- [AR Music Room User Guide](https://github.com/kuscholar/ARMusicRoom/files/8765509/AR.Music.Room.User.Guide.pdf)
- [Demo video](https://youtu.be/_T7A59LeHN8)


## DEVICE AND REQUIREMENT

- The app runs on iOS devices and Android devices, it has been tested on iPhone 11 Pro Max with
iOS version 15.4. Other iPhones with an iOS version 11.0 or higher should work as well.

- To run the app on an Android device, simply download the ARMusicRoom1.2.apk file and install it on the device and run.

## INSTALLATION

1. Download the build folder ‘MusicRoomX.X’ from the box folder on to a Mac
    OS computer.
2. Open the folder on your Mac, and double click on ‘Unity-iPhone.xcodeproj’.

![image](https://user-images.githubusercontent.com/61807135/206827357-4d6e4597-388d-49ff-b7c6-b136ce9eadf9.png)

> **_NOTE:_** XCode is required, please go to AppStore and download and install XCode
if you don’t have it on your Mac.

3. After opening the XCode project, click on Unity-iPhone icon on the left.

![image](https://user-images.githubusercontent.com/61807135/206827404-b317694a-d610-4673-9355-6e8a55443bf2.png)


4. Connect your iPhone to your Mac, and press where the hammer icon is
    located. Your iPhone should be shown up as an option, then click on your
    iPhone icon.

![image](https://user-images.githubusercontent.com/61807135/206827415-3c24fc85-fbb1-420e-a4d3-f8110c1f4933.png)

5. Go to ‘Signing & Capabilities’ tab bar, and check ‘Automatically manage
    signing’.
![image](https://user-images.githubusercontent.com/61807135/206827424-8fcb7b6a-a236-45d3-a4db-def68300feea.png)


6. Click on ‘Team’ bar, and select your own account. If you don’t have one,
    click on ‘Add an Account...’ and add your account, then select it.
    
![image](https://user-images.githubusercontent.com/61807135/206827458-e51da4d1-a093-4a5c-af81-7aeba55cff94.png)

7. In ‘Bundle Identifier’ text field, use the format
    ‘com.yourname.yourappname’, and make sure the identifier is unique.
    
    ![image](https://user-images.githubusercontent.com/61807135/206827477-e5f8efa5-2672-4c77-a364-2b2157762efe.png)

8. Click on ‘Run’ and wait for it to be deployed on your phone.

![image](https://user-images.githubusercontent.com/61807135/206827501-5ebef5ce-1346-40f0-8205-91cf9697f11d.png)

## FEATURES

- You can simply run the app and follow the instructions on the screen.
- There will be 2D and 3D UI buttons, click on each of them and check them
    out.
    
    ![image](https://user-images.githubusercontent.com/61807135/206827515-02d912da-ff15-4571-b5cb-bbb5520b8696.png)

- The reset button on the top left is for resetting the scene, and you will be
    directed to the very beginning and start all over again.


- The UI button on the top right is for toggling the generating 3D models UI
    buttons, clicking on it will hide the buttons on the bottom, and clicking again
    will show them.
- The color button next to the UI button is for displaying 3D UI above the piano,
    this requires you to place a piano in the scene first.
- To place items, simply click on the four buttons on the bottom in the
    following order: “Play Ground”, “Piano”, “Chair”, “Guitar”.
    
    ![image](https://user-images.githubusercontent.com/61807135/206827519-089ab227-e71a-4bc4-a5b0-2c3bc59ef54a.png)

- After finishing, you will be indicated by the text instruction and the piano
    music sound.

## ISSUES

The raycast feature may not perform stably depending on your device. If an item is
placed in the wrong place, simply re-tap on the button and place it in the right place
again.


