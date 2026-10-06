# master-farmer-assets

GUI artwork for the **Master Farmer** launcher (Sylvanas). The launcher downloads
`gui/*.png` from this repo on first use and caches them, so the plugin needs no
local image files.

Rebuild the images with `tools/build_gui_assets.py` in the launcher project, copy
them into `gui/`, and bump `config.asset_version` in the launcher so every PC
downloads the new set.
