[English](README.md) | **简体中文**

# TinyFarm
**TinyFarm** 是一个使用 Entt, SDL3, OpenGL, MiniAudio, Freetype, glm, ImGui, nlohmann-json 和 Tiled 开发的跨平台 C++ 农场游戏。

> 本项目是一个教学演示项目，是 “[C++ 游戏开发之旅](https://cppgamedev.top/)” 系列教程的第 5 篇。

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

## 网页版试玩
[TinyFarm](https://wispsnow.github.io/TinyFarm/)

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
```

> 注意：本项目使用了付费素材 [farm-rpg](https://emanuelledev.itch.io/farm-rpg), 因版权原因，仓库中不提供原始素材文件，只有图片占位符可确保程序正常运行（用于游戏开发学习已足够）。

> 如果你想要实现演示项目中的效果，可购买该素材后，将所有内容复制到 `assets/farm-rpg` 文件夹中（覆盖原始文件）即可。

如果你在下载此项目时遇到问题（尤其是在中国大陆网络环境下），可从 [百度网盘](https://pan.baidu.com/s/1lS0-vEciTGHUweWZo7Tpfg?pwd=3v7a) 中下载全部源码（包含第三方库）进行编译。

> 网盘中的项目源码版本可能落后于GitHub仓库，建议下载本仓库内容，然后拷贝网盘中的第三方库源码（`external`文件夹中内容）到本仓库进行编译。

# 致谢
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

## 联系方式

如需支持或反馈，请通过本仓库的 Issues 版块反馈。您的反馈对于改进这一系列教程至关重要！

## 请我喝咖啡
<a href="https://ko-fi.com/ziyugamedev"><img src="https://storage.ko-fi.com/cdn/kofi2.png?v=3" alt="Buy Me A Coffee" width="200" /></a>
<a href="https://afdian.com/a/ziyugamedev"><img src="https://pic1.afdiancdn.com/static/img/welcome/button-sponsorme.png" alt="Support me on Afdian" width="200" /></a>

## QQ 交流群及我的微信二维码

<div style="display: flex; gap: 10px;">
  <img src="https://theorhythm.top/personal/qq_group.webp" width="200" />
  <img src="https://theorhythm.top/personal/wechat_qr.webp" width="200" />
</div>
