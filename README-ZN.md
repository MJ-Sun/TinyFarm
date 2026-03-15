[English](README.md) | **简体中文**

# TinyFarm
**TinyFarm** 是一个使用 Entt, SDL3, OpenGL, MiniAudio, Freetype, glm, ImGui, nlohmann-json 和 Tiled 开发的跨平台 C++ 农场游戏。

## 操作说明
- 移动：`W/A/S/D` 或方向键 `↑/←/↓/→`
- 攻击/使用：`鼠标左键` 或 `K`
- 交互：`F`
- 角色灯光切换（夜晚有效）：`L`
- 暂停：`P` 或 `Esc`
- 物品栏：`I`
- 快捷栏：`Tab`
- 快捷栏选槽：`1` ~ `0`（对应 1~10）
- 镜头缩放/重置：`鼠标滚轮/中键`
- 游戏层调试UI：`F5` / `` ` ``
- 引擎层调试UI：`F6`/`\`

## 游戏截图
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf1.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf2.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf3.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf4.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf5.webp" style='width: 640px;'/>
<img src="https://theorhythm.top/gamedev/TF/screen_shot_tf6.webp" style='width: 640px;'/>

## 第三方库
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

## 构建指南
依赖项将通过 Git FetchContent 自动下载，构建非常简单：
```bash
git clone https://github.com/WispSnow/TinyFarm.git
cd TinyFarm
cmake -S . -B build
cmake --build build
