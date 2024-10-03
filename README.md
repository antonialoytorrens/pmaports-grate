# Unofficial pmaports for Tegra and non-NEON systems

⚠️ **Disclaimer**: You are on your own! I seldomly mantain these scripts, and you will mostly *NOT* have any form of user support. Binaries will not be redistributed in any type or form, I only provide the build scripts.

---

This is a completely unofficial pmaports for non-NEON systems for PostmarketOS / Alpine Linux, aimed at Tegra20 chips mostly.
It contains the following packages:
* mesa-grate: WIP Mesa for Tegra systems with partial OpenGL 1.1 implementation (basic glxgears).
* palemoon-noneon: Palemoon for non-NEON systems (see palemoon-noneon/README.md).
* sdl2-noneon: SDL2 for non-NEON systems (see sdl2-noneon/README.md).

## Status
- Palemoon: Builds successfully and works on Alpine Linux 3.18 / PostmarketOS 23.06.
- SDL2: ?
- Mesa-grate: ?

## Credits
- Palemoon: Credits to [https://github.com/tanertas/aports/tree/palemoon/testing/palemoon](tanertas), the original source where I picked most of the `APKBUILD` files.
- mesa-grate: Credits to [https://gitlab.com/ryang2678/pmaports/-/tree/mesa-grate-elfutils/main/mesa-grate](ryang2678), the original source where I picked most of the `APKBUILD` files.

## Screenshots
### PostmarketOS 23.06 / Alpine 3.18
![Pale Moon 22.9.4 running on PostmarketOS 23.06 on an Asus Transformer TF101](assets/img/PostmarketOS/23.06/pale-moon-showcase-pmos.png)

![Pale Moon 22.9.4 (fullscreen) running on PostmarketOS 23.06 on an Asus Transformer TF101](assets/img/PostmarketOS/23.06/pale-moon-tf101.png)

## TODO
Try to build a more recent Palemoon version.
Bump to a newer PostmarketOS / Alpine version.
(Maybe) Deb builds?