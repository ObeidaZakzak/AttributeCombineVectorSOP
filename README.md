# Attribute Combine Vector SOP
Houdini HDA that combines vector attributes using vector-specific operations, such as :
- Cross product
- Vector projection
- Vector rotation

Blending between results can be done with spherical interpolation, which has accurate results for blending vectors.

Note : Houdini 20.0 has a native implementation of spherical interpolation, using `slerpv` VEX function. This HDA uses `slerpv`. If you are using an older Houdini version, please download version 1.1, as it has a custom implementation of `slerpv` to avoid incompatibility. If you download version 1.1 for Houdini 20, the HDA will still use Houdini's native implementation of `slerpv`, and the custom implementation will only be used for older versions.

Check the HDA's help card as well as the examples hip file to learn basics and see how to use it with a couple of workflows.

[![](https://img.youtube.com/vi/VPySvru8FpU/0.jpg)](https://youtu.be/VPySvru8FpU?si=twc_F4ePi5fgOa-0)
