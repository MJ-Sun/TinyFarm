**English** | [简体中文](README-ZN.md)

# TinyFarm
**TinyFarm** is a cross-platform C++ farming game developed using Entt, SDL3, OpenGL, MiniAudio, Freetype, glm, ImGui, nlohmann-json, and Tiled.

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
