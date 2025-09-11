[Japanese/日本語](README_JP.md)

# RVX by anddea

Pre-patched YouTube and YouTube Music APKs together with modules based on anddea’s patches.

The builds are automatically generated using [GitHub Actions](https://github.com/Sanka1610/RVX-by-anddea/actions/workflows/build.yml).

## Supported Targets

  - ### Common

     - Architectures : arm64-v8a
   
     - Root Managers : Magisk-based, KernelSU-based, APatch-based

  - ### Apps

    - #### YouTube

      - Versions : Stable, Latest

        - Note : Latest is intended for devices with YouTube pre-installed. It may be unstable, so use with caution.

    - #### YouTube Music

      - Versions : Stable


## Download

You can get the latest release [here](https://github.com/Sanka1610/RVX-by-anddea/releases/).

Choose either the module or the patched APK according to your environment.


## Notes

### Root Environment

- Works with Zygisk or its alternatives.

- If using Zygisk Assistant, SU permissions must be granted to YouTube and YouTube Music.

- To prevent automatic updates from the Play Store,using [zygisk-detach](https://github.com/j-hc/zygisk-detach) is recommended.

### Non-Root Environment

- Requires [MicroG / GmsCore](https://github.com/microg/GmsCore) or an alternative.

- Installed as a separate app from the original YouTube app.

- Since zygisk-detach cannot be used in non-root, disable automatic updates from the Play Store manually.

## Credits

### [**j-hc**](https://github.com/j-hc)

  - [revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)

### [**anddea**](https://github.com/anddea)

  - [ReVanced Patches](https://github.com/anddea/revanced-patches)
