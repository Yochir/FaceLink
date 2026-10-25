# FaceLink

Face tracking for VRChat from your Android phone. FaceLink tracks your face with the
front camera and streams it to [VRCFaceTracking](https://github.com/benaclejames/VRCFaceTracking)
on your PC.

On Google Pixel phones (Tensor chips) it runs at 60 fps on the phone's AI chip. Other
phones use the GPU.

## Download

Get **FaceLink-1.0.apk** from the [latest release](../../releases/latest).

## Install

1. Open the APK on your phone (from Files, Chrome or wherever you downloaded it).
2. If Android asks, allow that app to **install unknown apps**, then go back and tap **Install**.
3. If Google Play Protect warns that it doesn't recognise the app, choose to install anyway.

Android 9 or newer, 64-bit.

## Set up

1. On the PC, run VRCFaceTracking with a module that receives on UDP port 11111.
2. Phone and PC on the same Wi-Fi.
3. Open FaceLink and enter your PC's IP address, or tap **Auto Detect PC Running VRChat**
   (VRChat must be running).
4. Put the phone where it will sit while you play, then run **Face** calibration in Settings.

## Updating

Install the new APK over the old one. Your settings are kept.
