# se360-install

Public install files for **Space Explorers 360** (native Steam Frame player).

[![Install with FramePort](install-with-frameport.svg)](https://frameport.app/install?manifest=https%3A%2F%2Ffivedegreesvr.github.io%2Fse360-install%2Fse360-vr.framedrop.json)

Needs [FramePort](https://frameport.app). The button names the Steam entry from the manifest and verifies the download.

- `se360-vr-linux-arm64.zip`: ARM64 build for drag-and-drop into FramePort.
- `se360-vr.framedrop.json`: install manifest (shared framedrop.install/v1 format).

## Artwork

Steam library art, all public-domain NASA photography (see the private repo's
`player/sideload/artwork/SOURCES.md` for the exact photos). FramePort picks
up `artwork/icon.png` automatically at install; apply the rest per game in
FramePort under **Name and artwork → Your own images**:

- `artwork/icon.png` (512×512): Steam icon, also the install dialog image.
- `artwork/portrait.jpg` (600×900): library grid cover.
- `artwork/landscape.jpg` (920×430): wide banner.
- `artwork/hero.jpg` (1920×620): game page backdrop.
- `artwork/logo.png`: transparent title logo drawn over the hero.
