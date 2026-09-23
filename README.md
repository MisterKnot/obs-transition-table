# Transition Table for OBS Studio

Plugin for OBS Studio to add a Transition Table to the tools menu.

This repository is a fork of the original [obs-transition-table](https://github.com/exeldro/obs-transition-table) project by [Exeldro](https://github.com/exeldro).

## Ubuntu 26.04 compatibility build

This fork provides an unofficial Ubuntu 26.04 compatible Debian package for Transition Table 0.3.1.

The original project, source code, and plugin are maintained by Exeldro. The Ubuntu 26.04 package provided by this fork is a compatibility build and is not an official Exeldro release.

## Download

For official upstream releases and project information:
https://obsproject.com/forum/resources/transition-table.1174/

Ubuntu 26.04 users can download the compatibility package from this fork's GitHub Releases page.

## Build

- Build OBS Studio: https://obsproject.com/wiki/Install-Instructions
- Check out this repository to UI/frontend-plugins/transition-table
- Add `add_subdirectory(transition-table)` to UI/frontend-plugins/CMakeLists.txt
- Rebuild OBS Studio

## Credits

Original project and source code: [Exeldro](https://github.com/exeldro)

Inspired by https://github.com/admshao/obs-transition-matrix

Ubuntu 26.04 compatibility package: MisterKnot

## License

Transition Table is distributed under the GNU General Public License v2. See [LICENSE](LICENSE).

## Donations

Support the original author:
https://www.paypal.me/exeldro
