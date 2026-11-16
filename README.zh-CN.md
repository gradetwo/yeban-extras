# yeban-extras · 夜半扩展仓

[English](README.md) | **简体中文**

夜半（Yeban）主程序之外的扩展内容仓：demo 工程、各曲风的模板工程、音源、预设与插件都放在这里，与主仓分开管理、分开授权。

主仓：[gradetwo/yeban](https://github.com/gradetwo/yeban) · 官网：<https://yeban.wangda.today>

Extras for the Yeban DAW — demo projects, genre template projects, sound libraries, presets and plugins, kept separate from the main repository.

## 目录

| 目录 | 内容 |
|---|---|
| `demos/` | 可直接打开的 demo 工程。一个 demo 一个子目录，内含工程文件与说明（内容、所用音源与预设、许可）。 |
| `templates/` | 各曲风的模板工程（流行、摇滚、电子、民谣等）。一个曲风一个子目录，打开即可在此骨架上创作。 |
| `sounds/` | 音源与采样库（SFZ 等）。大文件走 Git LFS；每个音源注明来源与许可。 |
| `plugins/` | 夜半插件，如渲染完成后一键发布、分享到多平台。一个插件一个子目录，自带说明与许可。 |
| `presets/` | 乐器与效果器预设包。 |

## 使用

- demo 与模板工程：下载后用夜半打开即可。工程引用的音源若在本仓 `sounds/` 下，按各工程说明里的相对路径放置。
- 音源：克隆本仓前先装 [Git LFS](https://git-lfs.com)（`git lfs install`），否则拉到的只是指针文件，不是音频本体。
- 插件：安装与启用方式见各插件子目录内的说明。

## 许可

本仓内容按目录分别授权，以各子目录内的 `LICENSE` 或说明为准。

- `plugins/` 下的代码未单独注明时，与主仓一致（GPL-3.0-only）。
- 工程、音源、预设等内容未单独注明时，版权归各自作者所有；使用或再分发前先看对应目录的说明。

## 贡献

欢迎以 PR 形式添加内容。每个内容项自带一份简短说明：是什么、怎么用、来源与许可。
