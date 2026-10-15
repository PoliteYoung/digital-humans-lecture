# Student Exercise: Bring Your Scene into VR

**Goal:** Make a small Unity VR experience and try it on **PICO** using the workflow taught earlier.

**A standalone build or PC streaming are both welcome.** Choose any Unity version, render pipeline, XR tools or permitted plugins that work for you. Getting your own VR experience running is already a good achievement.

## What to try

1. Import a permitted Gaussian scene and check its orientation, scale and viewpoint. You are encouraged to choose a different environment.
2. If feasible and permitted, add a volumetric performer such as Bass. Move around it and view it from different sides to show that it is 3D, not flat video.
3. Try one simple interaction: teleport, an information panel or proximity activation.
4. Experience your scene in VR on PICO, **through a build or streaming**. Check head tracking and your intended controls.

Start small and simplify when needed. A small working scene is better than an unfinished complex project. Explain any features you could not get working.

## Resources

- **Renderer:** [Gsplat Unity](https://github.com/wuyize25/gsplat-unity).
- **Dynamic playback:** [DynGsplat Unity](https://github.com/HiFi-Human/DynGsplat-unity).
- **Performer/data:** [DualGS](https://github.com/HiFi-Human/DualGS) and [dataset instructions](https://github.com/xyi1023/DualGS_Dataset). The linked Bass capture is `4K_Actor4_Bass`. Raw multi-view data needs DualGS reconstruction and DynGsplat compression to become DGS metadata plus data blocks. A prepared DGS sequence can be imported directly.
- **Suggested scene:** search **dreams lab** in the [SuperSplat community](https://superspl.at/). Verify the creator and reuse permission.
- **SOG to PLY:** import the full bundle in the [SuperSplat editor](https://superspl.at/editor) and export uncompressed PLY. This demo's importer accepts Gaussian PLY with SH degree 0–3; other plugins may support other formats.
- **Alternatives:** [Inria Gaussian models](https://github.com/graphdeco-inria/gaussian-splatting), Hugging Face, or your own permitted capture.

Check asset/plugin permissions before use or sharing. Confirm DynGsplat student-use and performer-display permissions with the instructor; do not redistribute restricted SDKs or portraits without permission.

## Share what you made

- A short video of your scene being experienced in VR on PICO; **build and streaming demonstrations both count**.
- Your playable build **or** project/run instructions, where sharing is permitted. An APK is optional.
- A short **English README**: what you made, how to try it, resource sources and any limitations.

No fixed software version, numerical performance target or research evaluation is required. **The main success is making something that works in VR.**

[English demo video](TutorialVideo/GSdemo_Tutorial_EN.mp4) · [Chapters](TutorialVideo/CHAPTERS.md)
