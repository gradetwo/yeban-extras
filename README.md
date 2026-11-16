# yeban-extras · Yeban Extras

**English** | [简体中文](README.zh-CN.md)

Extras for the Yeban DAW, kept separate from the main repository and licensed separately: demo projects, genre template projects, sound libraries, presets and plugins.

Main repository: [gradetwo/yeban](https://github.com/gradetwo/yeban) · Website: <https://yeban.wangda.today>

## Contents

| Directory | Contents |
|---|---|
| `demos/` | Demo projects that open directly in Yeban. One subdirectory per demo, containing the project files and a note (contents, sounds and presets used, license). |
| `templates/` | Template projects by genre (pop, rock, electronic, folk, …). One subdirectory per genre — open one and start creating on its skeleton. |
| `sounds/` | Sound libraries and sample packs (SFZ and others). Large files are stored with Git LFS; every library states its source and license. |
| `plugins/` | Yeban plugins, e.g. one-click publishing after a render, or sharing to multiple platforms. One subdirectory per plugin, with its own readme and license. |
| `presets/` | Preset packs for instruments and effects. |

## Usage

- Demo and template projects: download and open in Yeban. If a project references sounds from this repository's `sounds/`, place them at the relative paths given in the project's note.
- Sounds: install [Git LFS](https://git-lfs.com) (`git lfs install`) before cloning, otherwise you will only get pointer files instead of the actual audio.
- Plugins: see the readme inside each plugin's subdirectory for installation and activation.

## License

Content in this repository is licensed per directory; the `LICENSE` file or note inside each subdirectory governs.

- Code under `plugins/` is under the same license as the main repository (GPL-3.0-only) unless stated otherwise.
- Projects, sounds, presets and other content remain the copyright of their respective authors unless stated otherwise; check the note in the corresponding directory before use or redistribution.

## Contributing

Contributions via pull request are welcome. Every item must carry a short note: what it is, how to use it, its source and its license.
