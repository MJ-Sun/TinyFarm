**English** | [简体中文](README-ZN.md)

# TinyFarm
**TinyFarm** is a cross-platform C++ farming game developed using Entt, SDL3, OpenGL, MiniAudio, Freetype, glm, ImGui, nlohmann-json, and Tiled.

> This project is an educational demonstration project and is the 5th part of the "[C++ Game Development Journey](https://cppgamedev.top/)" tutorial series.

## Controls
- Move: `W/A/S/D` or Arrow Keys `↑/←/↓/→`
- Attack/Use: `Left Mouse Button` or `K`
- Interact: `F`
- Toggle Character Light (night only): `L`
- Pause: `P` or `Esc`
- Inventory: `I`
- Hotbar: `Tab`
- Hotbar Slot Selection: `1` ~ `0` (corresponding to slots 1~10)
- Camera Zoom/Reset: `Mouse Wheel/Middle Button`
- Game Layer Debug UI: `F5` / `` ` ``
- Engine Layer Debug UI: `F6`/`\`

## Web Demo
[TinyFarm](https://wispsnow.github.io/TinyFarm/)

## Game Screenshots
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf1.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf2.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf3.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf4.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf5.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf6.webp" style='width: 640px;'/>

## Third-Party Libraries
* [EnTT](https://github.com/skypjack/entt)
* [SDL3](https://github.com/libsdl-org/SDL)
* [MiniAudio](https://miniaud.io/)
* [FreeType](https://github.com/freetype/freetype)
* [HarfBuzz](https://github.com/harfbuzz/harfbuzz)
* [glm](https://github.com/g-truc/glm)
* [ImGui](https://github.com/ocornut/imgui)
* [nlohmann-json](https://github.com/nlohmann/json)
* [spdlog](https://github.com/gabime/spdlog)
* [GoogleTest](https://github.com/google/googletest)

## Build Guide
Dependencies will be automatically downloaded via Git FetchContent, making the build process very simple:
```bash
git clone https://github.com/WispSnow/TinyFarm.git
cd TinyFarm
cmake -S . -B build
cmake --build build
```

> Note: This project uses paid assets from [farm-rpg](https://emanuelledev.itch.io/farm-rpg). Due to copyright reasons, the repository does not include the original asset files, only image placeholders to ensure the program runs properly (sufficient for game development learning purposes).

> If you want to achieve the effects shown in the demo project, you can purchase the asset pack and copy all contents to the `assets/farm-rpg` folder (overwriting the original files).

If you encounter problems downloading this project (especially in mainland China network environment), you can download the complete source code (including third-party libraries) from [Baidu Netdisk](https://pan.baidu.com/s/1lS0-vEciTGHUweWZo7Tpfg?pwd=3v7a) for compilation.

> The project source code version in the Netdisk may lag behind the GitHub repository. It is recommended to download this repository and then copy the third-party library source code (`external` folder contents) from the Netdisk to this repository for compilation.


# Acknowledgements
- sprite & UI
    - https://emanuelledev.itch.io/farm-rpg
- font
    - https://timothyqiu.itch.io/vonwaon-bitmap
- sound
    - https://ateliermagicae.itch.io/fantasy-ui-sound-effects
    - https://freesound.org/people/Benboncan/sounds/69422
    - https://freesound.org/people/michaelperfect/sounds/710298/
    - https://freesound.org/people/soundscalpel.com/sounds/110393/
    - https://freesound.org/people/Valenspire/sounds/699492/
    - https://freesound.org/people/wobesound/sounds/488393
    - https://kasse.itch.io/ui-buttons-sound-effects-pack
    - https://mixkit.co/free-sound-effects/garden/
    - https://mmvpm.itch.io/platformer-sound-fx-pack
    - https://pixabay.com/sound-effects/pick-axe-striking-rocks-2-63070/
    - https://tommusic.itch.io/free-fantasy-sfx-and-music-bundle
- music
    - https://nakatomo.itch.io/spring-music
- Sponsors: `sino`, `李同学`, `swrainbow`, `爱发电用户_b7469`, `玉笔难图`, `jl`

## Contact

For support or feedback, please use the Issues section of this repository. Your feedback is essential for improving this tutorial series!

## Buy Me a Coffee
<a href="https://ko-fi.com/ziyugamedev"><img src="https://storage.ko-fi.com/cdn/kofi2.png?v=3" alt="Buy Me A Coffee" width="200" /></a>
<a href="https://afdian.com/a/ziyugamedev"><img src="https://pic1.afdiancdn.com/static/img/welcome/button-sponsorme.png" alt="Support me on Afdian" width="200" /></a>

## QQ Group and My WeChat QR Code

<div style="display: flex; gap: 10px;">
  <img src="https://theorhythm.top/personal/qq_group.webp" width="200" />
  <img src="https://theorhythm.top/personal/wechat_qr.webp" width="200" />
</div>
