Creative Commons Non Commercial 3.0 License

Icon images from iconmonstr.com see website for license terms

Some additional icons from metroicon.net courtesy of Piers

## Arctic Zephyr Reloaded for CPM builds

Modified version of [beatmasterRS's skin](https://github.com/beatmasterRS/skin.arctic.zephyr.mod) for [CoreELEC CPM builds](https://github.com/cpm-code/xbmc).
- modify PlayerProcessInfo window
- add button to OSD to trigger PlayerProcessInfo
- add button to OSD to trigger PlayerDebug
- hide OSD during pause by a remote control when "Hide play/pause info" is enabled in settings
- enable seeking with arrow buttons and show Seekbar and OSD Info when PlayerProcessInfo window is active
- add compact view of PlayerProcessInfo window (toggled by middle button) to only display dynamic info

### Recommended skin settings to hide OSD during pausing, in Video/Music OSD

When the "Hide play/pause info" is enabled in settings of the skin:

- hide OSD of any of the OSD views during pause by a remote control (e.g. Kore / Yatse app)
- remove annoying background of Reloaded OSD view

Skin settings:

- auto close OSD after delay: 5
- video OSD view mode: Reloaded
- show detailed info when video starts: off
- show detailed info when video is paused: disabled
- hide play/pause info: enabled

### Install and update skin

[Install and update the skin from zip file](https://kodi.wiki/view/Add-on_manager#How_to_install_from_a_ZIP_file) under releases, it will not touch the original one (it has different id).

