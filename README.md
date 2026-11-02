# More Bobs! source packages

All six manifests target Factorio `0.16`; newer game compatibility is not established by these files. This repository has no GitHub Releases.

| Package | Version | Manifest |
| --- | --- | --- |
| `morebobs` | `0.16.51` | [info.json](morebobs_0.16.51/morebobs_0.16.51/info.json) |
| `morebobs_bobsStackCrate` | `0.16.0` | [info.json](morebobs_bobsStackCrate_0.16.0/morebobs_bobsStackCrate_0.16.0/info.json) |
| `morebobs_flowcontrol` | `0.16.0` | [info.json](morebobs_flowcontrol_0.16.0/morebobs_flowcontrol_0.16.0/info.json) |
| `morebobs_shiny` | `0.16.1` | [info.json](morebobs_shiny_0.16.1/morebobs_shiny_0.16.1/info.json) |
| `morebobs_tweaks` | `0.16.2` | [info.json](morebobs_tweaks_0.16.2/morebobs_tweaks_0.16.2/info.json) |
| `morebobs_usefulsomething` | `0.16.0` | [info.json](morebobs_usefulsomething_0.16.0/morebobs_usefulsomething_0.16.0/info.json) |

Copy each inner directory containing `info.json` into your Factorio user data `mods` directory. The repository root and outer wrapper directories are not installable mods. Install required dependencies from each manifest: `morebobs` requires `boblibrary`; add-ons require `morebobs`, with some also requiring `ShinyIcons` or `Flow Control`. `?` marks optional dependencies. Original attribution and licenses remain in the package directories.
