# Student Exercise: Bring a Gaussian Scene into VR

**Course:** Interactive AI Systems: Design & Implementation

## Your goal

Build a small VR experience in Unity, install it on your **PICO headset**, and make it run as a standalone application. Reuse the Unity/PICO workflow from the earlier lessons.

**You may choose your Unity version, render pipeline, XR tools and rendering plugins.** The instructor's demo settings are examples, not assignment requirements. A simple working VR application is a good result; start small rather than trying to reproduce the entire laboratory.

## What to try

1. Choose a permitted Gaussian environment. You are encouraged to use a different scene from the instructor's demo.
2. Import it into Unity and check its orientation, scale and viewing position.
3. If feasible and permitted, add a recorded volumetric performer such as Bass. Move around it and view it from different sides to show that it is three-dimensional, not a flat video.
4. Add one simple interaction: teleport, an information panel, proximity activation, or another useful action.
5. Build, install and try the application on PICO. Check that head tracking and your intended controls work.

If a large scene or dynamic performer does not run well, reduce the scope. A smaller working VR scene is better than a complex project that cannot run. Explain any omitted features; ask the instructor if you need a different approach.

## Where to get resources

- **Static renderer:** [Gsplat Unity](https://github.com/wuyize25/gsplat-unity).
- **Dynamic playback plugin:** [DynGsplat Unity](https://github.com/HiFi-Human/DynGsplat-unity).
- **Performer/data workflow:** [DualGS](https://github.com/HiFi-Human/DualGS) and the [official dataset instructions](https://github.com/xyi1023/DualGS_Dataset). Cloning the code does not automatically provide a ready-to-play Bass Unity asset; use an authorized prepared sequence or follow the authors' training/export/compression workflow.
- **Suggested environment:** search **dreams lab** in the [SuperSplat community](https://superspl.at/). Check the scene identity, creator and reuse permission.
- **SOG to PLY:** open the complete bundle in the [SuperSplat editor](https://superspl.at/editor), then export **uncompressed PLY**. For this demo's importer, use SH degree 0–3 and check the Gaussian attributes. Other plugins may accept other formats. Do not simply rename the file extension.
- **Other scenes:** [Inria 3DGS](https://github.com/graphdeco-inria/gaussian-splatting) links pretrained models; you can also search Hugging Face or use your own permitted capture.

Use only assets and plugins you are allowed to use and share. Confirm DynGsplat student-use and performer-display permissions with the instructor before using that route. Do not redistribute restricted SDKs, private scans or portraits without permission.

## Show your result

- Provide an installable build/APK, within the permitted sharing scope.
- Record a short video **on the headset** showing that the application runs and demonstrating your interaction. Desktop Play mode or PC streaming alone is not the standalone result.
- Add a short **English README**: what you built, how to install/run it, where the assets/plugins came from, and any limitations. A project/source link is useful where sharing is permitted.

No specific Unity version, renderer, numerical performance target or research study is required. The main success is a VR application that you can install and run on PICO.

## Demonstration

[English tutorial video](TutorialVideo/GSdemo_Tutorial_EN.mp4) · [Video chapters](TutorialVideo/CHAPTERS.md)

The instructor demonstration is a desktop example, not an already verified PICO build. Original signage in the captured lab may contain Chinese; keep your own controls and explanatory text in English.
