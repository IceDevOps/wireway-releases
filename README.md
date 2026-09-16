# WirewayOpTi — desktop app downloads

WirewayOpTi reads a panel-layout DXF and produces the wireway cut plan, panel
layout, and the AutoCAD mounting-hole script.

**To install or update:** open the
[Releases](https://github.com/IceDevOps/wireway-releases/releases/latest)
page, download `WirewayOpTi.exe`, and put it anywhere (Desktop is fine). No
installer, no Python. Double-click to run.

- Windows SmartScreen may warn the first time because the file isn't
  code-signed — click **More info**, then **Run anyway**.
- The app keeps itself up to date: on startup it downloads a newer
  version in the background and applies it when you restart or close it.
- Before exporting a DXF for Wireway, hide the hardware and panel-cover
  layers — slotted hardware can be mistaken for duct.

This repository only hosts the built application. The source code lives in
a private ICE repository.
