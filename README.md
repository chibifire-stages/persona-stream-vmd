# vmd_motion for VRM

Plays VMD (MikuMikuDance motion) on a VRM humanoid in Godot 4: the VMD reader, the pose applier, a
`SkeletonModifier3D` that drives the skeleton and `VRMAnimator`, which maps MMD bones to the VRM humanoid. Nothing
else is kept (no demo UI, no camera, no sample assets).

`addons/vmd_motion` is MIT, from lox9973's VMDMotion and EIRTeam's VMDMotionGD. It needs V-Sekai's godot-vrm
(`https://github.com/V-Sekai/godot-vrm`, MIT) and its MToon addon under `addons/`; they are not copied into this
repository. The persona-stream manifest checks godot-vrm out at `model/thirdparty/godot-vrm`.

The VMD files are not included: most MMD motion carries its author's terms and no open licence was found.
