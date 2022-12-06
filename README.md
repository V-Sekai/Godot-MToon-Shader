Godot-MToon-Shader is meant to implement the same functionality and featureset as https://github.com/Santarh/MToon used in the VRM standard.

This addon is designed to be used together with https://github.com/V-Sekai/godot-vrm but may also be used as a standalone toon shader.

This version of MToon only supports Godot 4.0 and newer. To use MToon on Godot 3.x, use the `godot3` branch of godot-vrm, or [download it from the Asset Library](https://godotengine.org/asset-library/asset/964).

# Installation

## Godot 4.0 or newer

Install this addon by cloning this repository into the `addons` folder, or using `git submodule` - If used together with `godot-vrm`, it is critical that this repository be at `addons/Godot-MToon-Shader` within your Godot project.

To use the proper shader inspector, enable the MToon plugin in Project Settings -> Plugins -> Godot-MToon-Shader.

It is recommended to install [godot-vrm](https://github.com/V-Sekai/godot-vrm) or from the Asset Library once it becomes available there for 4.0

## Godot 3.x

This repository does not support versions prior to Godot 4.0

For VRM and MToon compatible with Godot Engine 3.2.2 or later, use the `godot3` branch of the [godot-vrm](https://github.com/V-Sekai/godot-vrm) repository.

# Tutorial (for Unity)

https://www.slideshare.net/VirtualCast/vrm-mtoon

# Known issues

Caveat: Scenes with realtime omni or spot lights will have clustering artifacts, because there is no current way to detect if a given light is directional. After some missing variables are added, we can provide a way to detect this.

## Credits

Thanks to the [V-Sekai team](https://v-sekai.org/about) and contributors:

- https://github.com/fire
- https://github.com/TokageItLab
- https://github.com/lyuma
- https://github.com/SaracenOne

For their extensive help testing and contributing code to Godot-VRM.

Special thanks to the authors of UniVRM, MToon and other VRM tooling

- The VRM Consortium ( https://github.com/vrm-c )
- https://github.com/Santarh
- https://github.com/ousttrue
- https://github.com/saturday06
- https://github.com/FMS-Cat
