# Changelog  
  
| modName    | ProbiTronics (PT)                                                 |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-NC-SA-4.0                                                   |
| author     | tdubic and zer0Kerbal                                             |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/191428-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/ProbiTronics)           |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/ProbiTronics)         |
| spacedock  | (https://spacedock.info/mod/3029)                                 |
| ckan       | ProbiTronics                                                      |

## Version 0.9.99.3-prerelease `<EDITION>` edition

* 19 Jul 2022
* Release for Kerbal Space Program [KSP 1.12.x]

### Summary

* Four New Parts
* 1.25m Service Module bottom node repaired

### Update

* [pt-probe-g.cfg] v1.0.1.0
  * bottom (only) node pointing up instead of down
  * thank you to u/Significant-Sir-690 for reporting this
  * also made node one size bigger (1 instead of 0)
  * [node_stack_bottom]
    * now = 0.0, -0.26, 0.0, 0.0, ***-1.0***, 0.0, ***1***, ***1***
    * was = 0.0, -0.26, 0.0, 0.0, ***1.0***, 0.0, ***0***
  * Add
    * [node_attach] = 0.0, 0.0, 0.0, 0.0, 1.0, 0.0, 0, 1

### Parts

* NEW
  * [ ] [pt-legAdapter-0625.cfg] v1.0.0.0
  * [ ] [pt-legAdapter-1875.cfg] v1.0.0.0
  * [ ] [pt-legAdapter-3750.cfg] v1.0.0.0
  * [ ] [pt-servicemodule-1875.cfg] v1.0.0.0
  * [ ] add @thumbs
* closes #57 - New Parts

### docs/

* Update
  * [README.md]
  * [PartsCatalog.md] v1.1.4.0

### Localization

* Update
  * Localization/
    * <tr-tr.cfg> v1.0.2.0
      * might need some tweaking
    * <en-us.cfg> v1.0.2.0
      * might need some tweaking
  * updates #7 - Localization - Master

---

### Parts## Version 0.9.99.2-prerelease `<MystLeissa>` edition

* 12 Jul 2022
* Release for Kerbal Space Program [KSP 1.12.x]

### Summary

* Four New Parts
* 1.25m Service Module bottom node repaired

### Parts

* NEW
  * [pt-servicemodule-0625.cfg] v1.0.0.0
  * [pt-servicemodule-3750.cfg] v1.0.0.0
  * [pt-prs-03125.cfg] v1.0.0.0
  * [pt-prs-0625.cfg] v1.0.0.0
  * add @thumbs
* closes #53 - New Parts

### docs/

* Updated [README.md]
* Replace [PartsInvoice.md] v1.1.3.2 with [PartsCatalog.md] v1.1.4.0

### Localization

* Update
  * Localization/
    * <tr-tr.cfg> v1.0.1.0
      * might need some tweaking
    * <en-us.cfg> v1.0.1.0
      * might need some tweaking
  * updates #7 - Localization - Master

### Update

* [pt-servicemodule-2500] v1.0.1.0
  * [advFlightControl] down from [specializedControl]
  * [node_stack_top]
    * now = 0.0, 1.20, 0.0, 0.0, 1.0, 0.0, 2, 1
    * was = 0.0, 1.12, 0.0, 0.0, 1.0, 0.0, 2, 1
* [pt-servicemodule-1250.cfg] v1.0.1.0
  * FLIP
  * [node_stack_bottom] pointing wrong way
  * thank you to [@MystLeissa](https://github.com/MystLeissa) for the report
  * [node_attach]
    * now = 0.0, 0.0, 0.0, 0.0, ***-1.0***, 0.0, 0, 1
    * was = 0.0, 0.0, 0.0, 0.0, ***1.0***, 0.0, 0, 1
* [pt-legAdapter-1250.cfg] and [pt-legAdapter-2500.cfg]
  * [ModuleToggleCrossfeed]
    * remove "" from localization strings
  * closes #52 - [Bug 🐞]: Bottom attach point of Service Module 1 Mk2 Doesn't attach
* Add
  * [DRAG_CUBES]
  * [ModuleCargoPart]
    * packedVolume = -1
  * [ModuleInventoryPart]
    * InventorySlots = 3
    * packedVolumeLimit = 180
    * will need future adjustments

### Status

* Issues
  * closes #48 - ProbiTronics (PT) 0.9.99.2-prerelease `<MystLeissa>` edition`
  * closes #49 - 0.9.99.2 Verify Legal Mumbo Jumbo
  * closes #50 - 0.9.99.2 Update Documentation
  * closes #51 - 0.9.99.2 Update Social Media

---

## Version 0.9.99.1-prerelease `<Onlar ne yaptı!? Neresi?!>` edition

* 03 Jun 2022
* Release for Kerbal Space Program [KSP 1.12.x]

### docs/

* Update
  * add Turkish (Türk)
    * [Attribution.md] v1.0.6.0
    * [Localizations.md] v1.1.3.1
    * [readme]
    * [releaseNotes]

### Localization

* Create
  * Localization/
    * <tr-tr.cfg>
    * by [urexpect](https://github.com/urexpect), Teşekkürler!
  * closes #44 - Turkish (Türk) <tr-tr.cfg>
  * updates #7 - Localization - Master

### Update

* [pt-rover-body-721.cfg]
  * [entryCost] up from 6200 to 30000
  * [cost] up from 5250 to 10120
  * [mass] down from 0.37 to 0.25
  * [ModuleCommand]
    * consumes [ElectricChange] up from 0.005 to 0.04
  * [ModuleReactionWheel]
    * consumes [ElectricChange] down from 0.25 to 0.09
  * Add
    * [ModuleKerbNetAccess]
    * [ModuleDataTransmitter]
    * [ModuleCoreHeat]
    * [radiatorMax] = 1.5

### Status

* Issues
  * closes #40 - ProbiTronics (PT) 0.9.99.1-prerelease `<Onlar ne yaptı!? Neresi?!>` edition`
  * closes #41 - 0.9.99.1 Verify Legal Mumbo Jumbo
  * closes #42 - 0.9.99.1 Update Documentation
  * closes #43 - 0.9.99.1 Update Social Media

---

## Version 0.9.99.0-adoption `<They Did What!? Where?!>` edition

* 21 May 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### docs/

* Update
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
* Add
  * [404-petunia.md]
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [PartInvoice.md] v1.1.3.1
  * [_config.yml]
  * closes #29 - docs/

### Parts

* Updating
* Linting
* Dusting
* Vacumming
* Painting
* [TACS-LS.cfg] v1.0.1.0
  * lots of stray right/closing braces `}`
* [kerbalOperatingSystem.cfg]
  * missing closes/right bracket `]`
* [BallProbe.cfg]
  * [description] accidentially split in twain, superklue applied

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds) (17.5mb to 6.93mb)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* add @thumbs
* closes #34 - add @thumbs
* closes #28 - Asset Updates

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
  * agency
  * flags
* run localizer
  * Parts to localize
    * [pt-servicemodule-2500.cfg]
    * [pt-legAdapter-1250.cfg]
    * [pt-legAdapter-2500.cfg]
    * [pt-probe-atv.cfg]
    * [pt-probe-ball.cfg]
    * [pt-probe-ball-parachute.cfg]
    * [pt-probe-ball-shield.cfg]
    * [pt-probe-g.cfg]
    * [pt-probe-sample-1250.cfg]
    * [pt-prs-1250.cfg]
    * [pt-prs-2500.cfg]
    * [pt-prs-3750.cfg]
    * [pt-rover-body-721.cfg]
    * [pt-servicemodule-1250.cfg]
  * closes #24 - Part Localization
  * closes #8 - English <us-en.cfg>
  * updates #7 - Localization - Master

### Status

* Issues
  * closes #3 - ProbiTronics 0.9.99.0-adoption `<They Did What!? Where?!>` edition
  * closes #4 - 0.9.99.0 Verify Legal Mumbo Jumbo
  * closes #5 - 0.9.99.0 Create Documentation
  * closes #6 - 0.9.99.0 Create Social Media

---

## Version 0.2.2.0-release `<First Contract>`

* Jul 20, 2014
* Released for Kerbal Space Program 0.24.0

* Price and other changes for 0.24 compatibility.
* Some smaller bug fixes.

### Status

* Issues
  * closes #27 - 0.2.2.0-release `<First Contract>`
  * closes #25 - Previous Releases

---

## Version 0.2.1.0-release `<All About da Science>`

* May 29, 2014
* Released for Kerbal Space Program 0.23.5  

* Ball probe
  * Barometer sensor
  * custom science experiment:
    * Advanced Atmospheric Research
* G-Probe
  * Gravity sensor
  * custom science experiment:
    * Magnetic field measurements
* On all parts configurations are changed on some more on some less.

### Status

* Issues
  * closes #26 - 0.2.1.0-release `<All About da Science>`
  * updates #25 - Previous Releases

---

## Version 0.2.0.0

* SP-1
  * sample probe
  * For better ways to bring back samples
* LA-2m
  * Leg adapter 2m
  * Your engine is to high and your legs don't touch the ground, not anymore
* LA-1m
  * Mesh collider fix
* SM I and SM II
  * texture changes and fix
  * New textures are .tga
  * you can delete .png textures for SM I and SM II parts.

---

## Version 0.1.9.0

* RU-3m MK I
  * probe, decoupler and parachute compartment in one
  * Add two Mk16 parachutes in middle attachment points
* LA-1m
  * Leg Adapter
  * gives you ability to use stock legs on longer engines.
* TAC Life Support - Added tac life support for parts
* SM MK I and SM MK II texture change
* RU-2m - height fix so parachute can fit inside

---

## Version 0.1.8.0

* SM MK I
  * Service module for Command Pod Mk1 (1m part).
* SM MK II
  * Service module for Command Pod Mk2-3 (2m-part).
* RB-721
  * Rover body
    * probe core inside
    * some batteries
    * small Radioisotope Thermoelectric Generator

---

## Version 0.1.7.0

* Two new Parts added
  * Attach this on top of your first or second stage. or better reusability of stock parts.
* RU-1m
  * probe, decoupler and parachute compartment in one
  * Add Mk16 parachute in middle attachment point
* RU-2m
  * probe, decoupler and parachute compartment in one
  * Add Mk16-XL parachute in middle attachment point

---

## Version 0.1.6.0

* ATV - attachment bug fixes and chaging parameters in cfg file
* Ball probe - cfg file chages
* G-probe - cfg file chages
  * added more electric charge and xenon gas

---
