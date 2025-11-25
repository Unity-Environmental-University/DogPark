# DogPark Release Hub

This repository only hosts packaged builds of **DogPark**, an Unreal Engine 5.5 learning game used by Unity Environmental University to teach canine training and animal behavior. All source code lives in the private development repository; visit this repo strictly to download the latest classroom-ready binaries.

## Downloading Builds
- Head to the **[Releases](../../releases)** tab.
- Pick the build tagged for your platform (Windows, macOS, or Linux).
- Each release includes:
  - A zipped build (`DogPark-1.0.1-Windows.zip`, `DogPark-1.0.1-Mac.zip`, etc.).
  - Release notes summarizing gameplay tweaks and educational guidance.

> Tip: If you only need the newest version, download the asset labeled **Latest**.

## System Requirements
| Platform | Minimum Specs | Notes |
| --- | --- | --- |
| Windows | 4-core CPU, 8 GB RAM, GTX 1060 / RX 580, 20 GB disk | Controller optional; keyboard/mouse fully supported. |
| macOS | Apple Silicon or Intel i5+, 8 GB RAM, 15 GB disk | Tested on macOS 13–15. Uses Metal. |
| Linux | Ubuntu 22.04 or equivalent, Vulkan-capable GPU | Launch via `DogPark.sh`. |

## Installation
1. Download the platform package from Releases.
2. Extract the archive to your preferred directory.
3. Run the executable:
   - Windows: `DogPark.exe`
   - macOS: right-click `DogPark.app` → *Open* (first run only)
   - Linux: `chmod +x DogPark.sh && ./DogPark.sh`

## Classroom Quick Start
1. Launch the game and choose **Story Mode** for guided lessons or **Free Play** for experimentation.
2. Set the **Difficulty (0–3)** in the settings menu to control reward timing and AI forgiveness.
3. Follow the on-screen instructor to practice Sit, Stay, Come, Fetch, etc...
4. Discuss outcomes with students using the post-session scoreboard and Ajax’s feedback cues.

## Reporting Issues
Because source code is hosted elsewhere, please:
1. Open a GitHub Issue in this repository.
2. Include the release tag, platform, steps to reproduce, and logs (`Saved/Logs/DogPark.log`).
3. Attach screenshots or short clips if behavior-specific.

## Need Source Access?
DogPark is owned by **Unity Environmental University**. If you require source access (curriculum integration, research collaboration, or localization), contact the program coordinator or email `xr@unity.edu` with your institution and intended use.
