# Student Exercise: Bring Your Scene into VR

**Goal:** Put a Gaussian scene and a volumetric performer into Unity, and experience them in a VR headset.

## Steps

1. **Import a Gaussian scene.** Check its orientation, scale and starting viewpoint. Feel free to pick a different environment from the demo.
2. **Add a volumetric performer.** Pick any sequence you like (the demo uses Bass). Walk around it in VR: it's truly 3D, not a flat video.
3. **Add one interaction:** teleport, an info panel, or proximity activation.
4. **Bring it into VR.** Put on your headset and check head tracking and your controls.

## Resources

- **Tutorial video (3 min):** [GSdemo_Tutorial_EN.mp4](TutorialVideo/GSdemo_Tutorial_EN.mp4) · [Chapters](TutorialVideo/CHAPTERS.md)
- **Gaussian renderer:** [Gsplat Unity](https://github.com/wuyize25/gsplat-unity)
- **Volumetric playback:** [DynGsplat Unity](https://github.com/HiFi-Human/DynGsplat-unity)
- **Performer:** [DualGS](https://github.com/HiFi-Human/DualGS) (code and training) + [DualGS dataset](https://github.com/xyi1023/DualGS_Dataset). The demo's Bass is `4K_Actor4_Bass`. Train with DualGS, compress with DynGsplat into a `.dgs` file plus data blocks, then import into Unity.
- **Scenes:** search **dreams lab** on [SuperSplat](https://superspl.at/), or use [Inria pretrained models](https://github.com/graphdeco-inria/gaussian-splatting), Hugging Face, or your own capture.
- **SOG → PLY:** open the full bundle in the [SuperSplat editor](https://superspl.at/editor) and export **uncompressed PLY** (SH degree 0–3).

## Submit

- A short video recorded **in the headset**.
- A short English README: what you built, how to run it, where your assets came from, and known issues.
- Your project, if you can share it.

*Use assets and plugins within their licenses. Don't publish other people's portraits or redistribute the DynGsplat SDK.*
