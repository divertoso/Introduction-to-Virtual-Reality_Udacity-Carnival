# Udacity Carnival
Starter project for the Udacity [VR Developer Nanodegree](https://br.udacity.com/course/vr-developer-nanodegree--nd017) program.

- Course: VR Developer Nanodegree
- Project: Udacity Carnival

### Summary
The Udacity Carnival consists of 3 Mini-Games: Plinko, Wheel of Fortune, and Coin Toss. With each game, you can earn points. After you earn 2000 points, you will receive a virtual classic Carnival prize!

![overview-image](https://user-images.githubusercontent.com/13722768/49696955-ae241080-fb98-11e8-8c46-b73301f700a8.JPG)

### Versions Used
- [Unity LTS Release 2018.2](https://store.unity.com/pt/download?ref=personal)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.170.0)
- TextMesh Pro (Native in 2018.2 version)


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is not included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.

### Transferring the App to your Android Device
1. Download Udacity-Carnival-Project via Clone or download. Then unzip it.

2. Unzip the Build.zip file inside the Udacity-Carnival-Project folder, which contains an apk for Android called carnival.apk from the Unity Project.

3. Plug in Phone to Computer. Your phone may be prompted to allow the Computer access to your phone data. Click Allow.

4. On PC, open the Windows Explorer or Finder. Click on your Android phone.

5. On PC, open the "SD Card" or it may be called "Card" folder, then open "download" folder. Drag and drop the carnival.apk file into that folder.

6. Eject your phone from the computer. On your phone, open an app, such as on Sony Xperia ZQ "My Files", that will allow you to see your downloads.

7. Tap on carnival.apk, a window may appear prompting you that your phone is set to block installation of apps obtained from unkown sources, if you want to test out the VR App on your phone, then go into settings.

8. You will see Unknown Sources or something similar, feel free to click OK to Allow this installation only. You will taken back to the installation of carnival.apk, click Install.

9. You should receive message: App installed. Open the VR App and if you have a Google Cardboard or similar mobile headset feel free to slide your Phone into it and put on the headset. Else you can still try out the app even without the headset.


### Open Project In Unity
Open Unity, then press Unity's Open button, select the Udacity-Carnival.

### Games preview and tips
#### Plinko
![Plinko](https://user-images.githubusercontent.com/13722768/49697748-3fe44b80-fba2-11e8-8f23-8bb71e08a0bb.jpg)
Hover the circle to the Plinko booth, the circle will grow, you'll notice a ball is oscillating left and right, tap the screen when you want to release the ball.

#### Wheel of Fortune
![Wheel of Fortune]((https://user-images.githubusercontent.com/13722768/49698157-37dada80-fba7-11e8-8f7d-5c93f973c073.jpg)
Hover the circle in the center of the wheel, you'll notice the circle becomes big, then tap the screen and the wheel will spin and then land on one of the wedges.

#### Coin Toss
![Coin Toss](https://user-images.githubusercontent.com/13722768/49697747-3fe44b80-fba2-11e8-9c76-0d4c3c059545.jpg)
Hover the circle on the coins, the circle will grow, then tap your screen, aim the coin at the center of the CoinToss booth and tap your screen to launch the coin

#### Game running on smartphone
![Sony Xperia ZQ](https://user-images.githubusercontent.com/13722768/49697746-3fe44b80-fba2-11e8-98d4-bd2ab7565f7e.jpg)

 
