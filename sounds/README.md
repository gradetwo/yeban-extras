# sounds · Sound libraries and samples

**English** | [简体中文](README.zh-CN.md)

Sound libraries and sample packs (SFZ and other formats). One subdirectory per library.

- Audio files are stored with Git LFS: run `git lfs install` before cloning, otherwise you will only get pointer files.
- Every library must state its source and license; do not add anything whose source or license is unclear.

## Download catalog

`catalog.json` in this directory is the machine-readable catalog the Yeban app reads for downloadable sound libraries (the Sound Library manager in the app's main menu). The app fetches it from the raw GitHub URL of this file on `main`.

Format:

```json
{
  "version": 1,
  "packs": [
    {
      "id": "unique-pack-id",
      "name": "Display name",
      "description": "Short description",
      "version": "1.0.0",
      "sizeBytes": 123456789,
      "sha256": "<lowercase hex sha256 of the archive file>",
      "url": "https://example.com/pack-archive.zip"
    }
  ]
}
```

Rules:

- `url` must be a direct link to the pack archive (zip or tar.gz). The app verifies `sizeBytes` and `sha256` after download and discards the download if either does not match.
- Keep `id` stable across versions of the same pack; bump `version` when the pack changes.
- An empty `packs` list is valid: the app then shows that no downloadable libraries are available yet.
