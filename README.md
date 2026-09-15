# PaceDownloader Extra Metadata

Extra Jellyfin-compatible metadata for Pace Downloader and related projects.

The repository is intended to hold metadata overlays that can be consumed by
Pace Downloader without mixing reusable metadata directly into the application
source tree.

## Onigashima Pace

Jellyfin metadata for Onigashima Pace is stored in `onigashima-pace/`.
The directory contains show-level metadata and two numbered season directories:

- `Season 1`: Onigashima
- `Season 2`: End of Wano

Episode titles, manga chapter ranges, anime episode ranges, runtimes, and release
dates come from the public
[Onigashima Paced Info spreadsheet](https://docs.google.com/spreadsheets/d/1HoYogAchoU5DWxVJzUy3eZcHMZk_hUmzUVnQm9KxeFI/edit?gid=0#gid=0).
The spreadsheet's End of Wano episode `03.5` is normalized to episode 4, and
source episode `04` is normalized to episode 5.

Image files are intentionally not included yet.

## License

Unless otherwise noted, metadata and other non-code content are licensed under
CC BY 4.0. Helper scripts and source code are licensed under MIT. See
[LICENSE.md](LICENSE.md).
