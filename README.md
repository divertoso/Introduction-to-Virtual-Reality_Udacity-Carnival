# Udacity Carnival
Starter project for the Udacity [VR Developer Nanodegree](https://br.udacity.com/course/vr-developer-nanodegree--nd017) program.

- Course: Introduction to Virtual Reality
- Project: Udacity Carnival

### Summary
The Udacity Carnival consists of 3 Mini-Games: Plinko, Wheel of Fortune, and Coin Toss. With each game, you earn points. When you earn 2000 points, you will receive a virtual classic Carnival prize!


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
