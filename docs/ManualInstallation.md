---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
ProbiTronics (PT)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# ProbiTronics (PT)

[Home](./index.md)

ProbiTronics is all about specialized probes and reusability parts. For Kerbal Space Program.


## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the ProbiTronics folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/ProbiTronics`
* Extract the package's `ProbiTronics/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/ProbiTronics` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/ProbiTronics`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/ProbiTronics`
* Extract the package's `GameData/ProbiTronics` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData/` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/ProbiTronics`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [ProbiTronics]
      + [Agencies]
        ...
      + [Compatibility]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * changelog.md
      * CC-BY-SA-4.0.txt
      * readme.htm
      * ProbiTronics.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
