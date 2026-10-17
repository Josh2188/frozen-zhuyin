# Character model

`konbini-girl.vrm` is pixiv's `VRM1_Constraint_Twist_Sample.vrm`, taken unchanged from the
[three-vrm](https://github.com/pixiv/three-vrm) repository (`packages/three-vrm/examples/models/`).

License, from the model's own VRM metadata:

- License: [VRM Public License 1.0](https://vrm.dev/licenses/1.0/)
- Copyright: (c) 2022 pixiv Inc.
- Avatar use: everyone · Commercial use: allowed · Redistribution: allowed · Modification: allowed · Credit: not required

The scene loads it with [@pixiv/three-vrm](https://www.npmjs.com/package/@pixiv/three-vrm) and drives its
skeleton from the scene's own walk / run / umbrella animation. If the file can't be loaded, the page falls
back to a simple built-in figure.
