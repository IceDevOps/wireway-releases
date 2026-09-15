# Wireway — desktop app downloads

Wireway reads a panel-layout DXF and produces the wireway cut plan, panel
layout, and the AutoCAD mounting-hole script.

**To install or update:** open the
[Releases](https://github.com/IceDevOps/wireway-releases/releases/latest)
page, download `Wireway.exe`, and put it anywhere (Desktop is fine). No
installer, no Python. Double-click to run.

- Windows SmartScreen may warn the first time because the file isn't
  code-signed — click **More info**, then **Run anyway**.
- The app checks this page on startup and shows an "Update available"
  link when a newer version has been published. Download the new
  `Wireway.exe` and replace the old one.
- Before exporting a DXF for Wireway, hide the hardware and panel-cover
  layers — slotted hardware can be mistaken for duct.

This repository only hosts the built application. The source code lives in
a private ICE repository.
