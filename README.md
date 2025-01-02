# ARCHIVED
# Please see [https://github.com/truckermudgeon/maps](https://github.com/truckermudgeon/maps)
# This repository has been made to support my main [application](https://github.com/Tumppi066/Euro-Truck-Simulator-2-Lane-Assist)
- The repo might or might not be maintained.
- Currently tested with 1.51.
  - NOTE: Will ONLY WORK ON 1.50 and above.
- The description below will not be updated.
- Download Visual Studio with C# (.net) support and then build the application.
  - After starting and loading the map, json files will be in the ts-map-canvas/bin/debug/ folder

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/E1E1NOC3P)

# Old description

This Application reads ATS/ETS2 files to draw roads, prefabs, map overlays, ferry lines and city names. It can also generate a route between two prefabs. This is an updated fork of [spedcord/ts-map](https://github.com/Spedcord/ts-map/)

To change the generated route you need to adjust the coordinates in TsMapper.cs line 916. This is not very user friendly, but that's mainly because I just needed a working proof of concept.

![Preview of the map](/docs/preview.jpg "Preview of the map")

### **Support for 1.44**

## Export Maps
Can now export maps as a tiled web map.

[Example with a max zoom level of 4](https://dariowouters.github.io/ts-tile-map-example/)

##### [Source](https://github.com/dariowouters/ts-tile-map-example)
## Map mod support
It can now load map mods.

Making all/specific map mods supported won't be a priority for me.

### Tested* map mods:

ETS2:
- TruckersMP map edits (cd_changes & hq_final)
- Promods Europe + Middle-East Add-On V2.60
- Rusmap V1.8.1
- The Great Steppe V1.2
- Paris Rebuild V2.3
- ScandinaviaMod V0.4
- Emden V1.02c (Doesn't show city name)
- Sardinia map V0.9 (Can't load some dds files)
- PJ Indo Map v2.5 (Can't load an overlay)

ATS:
- ProMods Canada V1.2.0
- Coast to Coast V2.6 (Can't load some dds files)
- US Expansion V2.4 (C2C Compatible)
- CanaDream Open Beta (ATS 1.32)
- Tonopah REBUILT V1.0.2
- Mexico Extremo 2.0.5
- Viva Mexico v2.4.8

\* The tested mods load and get drawn but I haven't looked at anything specific so it's always possible there will be some items missing or things will get drawn that shouldn't.

## Supported maps / DLC
- ATS
    - All map DLCs up to and including Wyoming.
- ETS2
    - All map DLCs up to and including Iberia.

#### Dependencies (NuGet)
- [Newtonsoft.Json](https://www.nuget.org/packages/Newtonsoft.Json)

#### Based on
[Original project](https://github.com/nlhans/ets2-map)
