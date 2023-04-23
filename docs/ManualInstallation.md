---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.0.0
Kerbal Inventory System No Fun (QBNF)
created: 19 Apr 2023
updated:

TEMPLATE: ManualInstallation.md v1.1.9.0
created: 01 Feb 2022
updated: 27 Mar 2023

based upon work by Lisias -->

# [Kerbal Inventory System No Fun (QBNF)][mod]

[Home](./index.md)

ModularManagement config script for removing "fun" items from Kerbal Inventory System. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `QuickBASIC` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/QuickBASIC/KerbalInventorySystemNoFun`
* Extract the package's `QuickBASIC/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/QuickBASIC` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/QuickBASIC/KerbalInventorySystemNoFun`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/QuickBASIC/KerbalInventorySystemNoFun`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/QuickBASIC/KerbalInventorySystemNoFun`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [QuickBASIC]
      + [KerbalInventorySystemNoFun][mod]
        ...
      + [Config]
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * GPL-2.0.txt
      * ManualInstallation.htm
      * readme.htm
      * KerbalInventorySystemNoFun.version
      ...
    + [UniversalStorage][us]
      ...
    ...
    * [ModularManagement (MM)][MM] or [Module Manager][mm]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Universal Storage (us)][US]
* *either*
  * [ModularManagement][MM]
  * [Module Manager][m-m]

[mod]: https://www.curseforge.com/kerbal/ksp-mods/KerbalInventorySystemNoFun "Kerbal Inventory System No Fun (QBNF)"

[MM]: https://www.curseforge.com/kerbal/ksp-mods/ModularManagement "ModularManagement (MM)"
[m-m]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[us]: https://forum.kerbalspaceprogram.com/index.php?/topic/68043-*/ "Universal Storage"

THIS FILE: CC BY-ND 4.0 by zer0Kerbal