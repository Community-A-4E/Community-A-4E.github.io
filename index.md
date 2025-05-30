![Community A-4E-C for DCS World, v2.3](https://cdn.discordapp.com/attachments/839130529488044052/1372309611578921000/a-4e-c-23.webp?ex=68264e6b&is=6824fceb&hm=ea8e57ee1d549c7edab36c7488397ffed2337d5df05d6eabc50cf8ccb4c0ff31&)

[Download](https://github.com/Community-A-4E/community-a4e-c/releases/latest) |
[Report a Bug](https://github.com/Community-A-4E/community-a4e-c/issues) |
[Discord](https://discord.gg/tQZbkTQ) |
[Github](https://github.com/Community-A-4E/community-a4e-c)

## About the A-4E-C Project

The A-4 was a cold war workhorse which proved to be a capable, reliable light attack aircraft to dozens of nations around the world. From the jungles of southeast Asia, to the desert of Sinai, to the coasts of South America, the scooter was a common sight above battlefields around the world for decades.

### A-4E-C Version 2.3 Community Update

Hello, A-4E-C pilots! We hope you are well. A-4E-C 2.3 brings greater compatibility with features introduced in DCS World 2.9, including fixes to radios, AGM-45 Shrikes, bomb fusing, and more. Thank you for flying the A-4E-C!
***DO NOT redistribute this mod without permission!***

### Contributing Developers

Gospadin, Heclak, Joshua Nelson, plusnine, Farlander, gyrovague, kryb/Archimaede, Merker, Jones, Nero

### Community Contributors

SkateZilla, uboats, Dr. Manius, LevelPulse, Cubeboy, Talo, GVad, OpticFlow, pohlinkzei, Coragem, nima3333, Sidekick65, SPINEG, Shadowfrost, Sport, Historiker, rudel-chw, Luciano, Malamem, HellesBelles, Bungo, Corsair016, FlyingHueman, JacobBadShot, JP Gabobo, Drofseh, Rob, ataribaby, Tanuki44, gcask, Nearblind, The Original HoggitDev Team, [Eric Haugen](http://erichaugen.bandcamp.com)

## Features

- Realistic external flight model and engine simulation
- Clickable cockpit
- Carrier landing and takeoff
- Air refueling
- AN/APN-153 Doppler Navigation Radar
- AN/ASN-41 Navigation Computer
- AN/ARC-51 UHF Radio
- AN/ARN-52 TACAN
- AN/ARA-63 MCL (ICLS)
- AN/APN-141 Radar Altimeter
- AN/APG-53A Radar
- AN/APR-25 Radar Homing and Warning System (ECM)
- AN/ALE-29A Chaff Dispensing System
- Automatic Flight Control System (AFCS)
- Approach Power Compensator (APC)
- AWE-1 Aircraft Weapons Release System (AWRS)
- CP-741/A Bombing Computer (CCRP)
- AGM-45 Shrike anti-radiation missile (SEAD)
- New weapons:
  - AN- series WWII munitions: M81, M88
  - MK4 HIPEG 20mm gunpod
  - Mk-77 napalm canister
- Unique sounds inside and outside the aircraft
- User manual (PDF and Kneeboard)

### A-4E-C Weapons Overview

<iframe width="560" height="315" src="https://www.youtube.com/embed/VEmy3XHWHKw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Version 2.3 Changelog: Featured Items

#### Added
- AGM-45 Shrike seeker head selection compatibility and sound response. There are some limitations that require pilot attention. After you rearm and before takeoff, a new set of new bindings (LSHIFT+1, 2, 4, 5) allow you to define the desired seeker head response for each station. Dynamic spawn A-4E-C units with AGM-45s in their loadout assume a MK 50 seeker.
- AN/APR-25 RHWS audio responses for SA-8, SA-10, SA-11, SA-13, and SA-19 search and tracking radars. Like the SA-3, these units give no audible launch indication.
- AN/ARA-63 MCL (ICLS) compatibility with Veinticinco de Mayo carrier.
- A-4E-C (Scooter) version number is recorded in DCS.log.

#### Changed
- AN/ARN-25 Automated Direction Finder (ADF) antenna rotation speed increased.
- CBU 1/A, 2/A, and 2/BA launchers now use the DCS standard weapons introduced with the F-4E.
- Instant Action Carrier Start should provide a clearer taxi path to the Stennis catapult.
- Exterior light animation improvements.
- External 3D model UV unwrap improvements for canopy, speedbrake, tailhook hinge, wheel well launch hooks, and refueling probe.
- Kneeboard manual updated with new information, and corrected a few typos.

#### Fixed
- Enabling TACAN and MCL/ICLS radios no longer cause crashes. Fixed TACAN bearing pointing North when off.
- MER and TER work with DCS bomb fusing.
- Non-axis throttle inputs properly disengage the APC.
- The ECM Panel REC warning light turns on if the AN/APR-25 RHWS is contacted by an SA-3 radar.
- AWRS STEP SINGLE and STEP SALVO bindings are no longer swapped.
- Raising flaps complies with Supercarrier crew "awaiting wing fold" requests.
- AI takeoff behavior on the Supercarrier (thanks Nearblind).

[See full changelog](https://github.com/Community-A-4E/community-a4e-c/blob/develop/CHANGELOG.md)

### Known Bugs and Incompatibilities

- Incompatible integrated graphics cards cause the view in the cockpit to black out.
- Incompatible with the following other mods: AH-6J Little Bird, CH-47 Chinook, and CH-53E Super Stallion, Chinese Aircraft Pack, Navy Equipment Mod.
- Mouse cursor capture using the UI override inputs occasionally fails to initialize. Reloading or restarting the mission usually fixes this.
- Streaming software sometimes omits certain cockpit audio.
- AN/ASN-41 Navigation Computer produces drift during active pause
- Huffer occasionally doesn't disconnect when plane moves
- Pilot occasionally blacks out when throttling up to hook up to catapult on SuperCarrier.

[See full issue list](https://github.com/Community-A-4E/community-a4e-c/issues)

## Installation

Failure to perform these steps will result in DCS World not recognizing the module, inability to use the module, input errors when using the module, or client integrity check failures on multiplayer servers that require them. Never install the A-4E-C files directly into your DCS World installation files! Installation size is around 1 GB.

### STEP 1: Upgrading from an older release

- If you are upgrading from an older version of the A-4E-C, completely uninstall your old version. If this is a brand new installation, skip this and move on to Step 2.

- First, uninstall the module's files from `%HOMEPATH%\Saved Games\DCS\Mods\aircraft\A-4E-C`

- Depending on how old a release you are upgrading from, you may need to reset your A-4E-C input bindings by deleting the contents of `%HOMEPATH%\Saved Games\DCS\Config\Input\A-4E-C`

### STEP 2: Installing the module files

- Installation instructions are identical for Standalone and Steam users alike.

- Download [the latest official A-4E-C release package](https://github.com/Community-A-4E/community-a4e-c/releases/latest). **Do not download directly from the Github repository**.

- Place the `Mods\aircraft\A-4E-C` folder in into your Windows user folder's Saved Games folder for DCS. For most users, this can be accessed by pasting `%HOMEPATH%\Saved Games\Saved Games\DCS` into a windows explorer address bar.

- If you have installed other DCS World mods, you might already have the `Mods` and `aircraft` folders indicated in the file path. If so, merge the new A-4E-C folder into the existing folders.

- **Never install the A-4E-C files directly into your DCS World installation files!**

### STEP 3: Verify installation

Launch DCS World. If your installation was successful, the A-4E-C theme icon appears as a option in the main menu:

![Image of DCS World Menu with A-4E-C Theme](verify.png)

### Installation Troubleshooting

Your correctly installed files should look something like the following image, substituting your Windows account name where the image displays *Partario*.:

![Image of A-4E-C installation](troubleshoot.png)

- If you have multiple DCS-related folders in your `%HOMEPATH%\Saved Games`, for example, `DCS`, or `DCS.openbeta`, and are unsure which folder your DCS World installation is using, locate the `dcs_variant.txt` file in the game files. If this file is present, its contents determines the folder structure your DCS World installation is using. Alternately, load DCS world and use the mission editor to create and save a mission. Search this mission file using Windows explorer to locate the proper folder structure.
- If you have installed the module correctly but it still isn't showing up, ensure it's enabled in the DCS Module Manager. Note that the A-4E-C is not alphabetically arranged along with the official modules in this list, and will be enumerated near the end of the list.
- If you are receiving an authorization error at launch, **you have incorrectly installed the module to your game files**. Remove any and all improperly installed files, then revisit the installation instructions above to correctly installing the module.
- If the A-4E-C icon in the DCS main menu shows a default DCS logo, is missing the theme background and music (or you experience crashes when loading a mission), you have incorrectly downloaded the module. [Download the latest official A-4E-C release package](https://github.com/Community-A-4E/community-a4e-c/releases/).
- If you can load a mission, but can't take control of the A-4E-C, ensure you have installed [Microsoft's Visual Studio 2015, 2017 and 2019 Redistributable libraries](https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0). For most users, this is `vc_redist.x64.exe`. Restart your computer after installation of the appropriate libraries.
- If you can't find the A-4E-C in the Mission Editor, ensure the historical mode filter is disabled by toggling the clock icon at the bottom of the screen, as shown in the following screenshot:

![Image of the Mission Editor pointing out the location of the Historical Filter](historical_filter.png) 

### In-Cockpit Troubleshooting

- When setting up your controls, press `LCTRL+Enter` to enable the controls indicator. Control binding information and tips for setting up your devices are provided in the kneeboard manual (`RSHIFT+K`).
- Always keep the canopy open when communicating with the ground crew.
- If you can't move the throttle, must first adjust the throttle step position. In order to do this, the throttle axis input must be at ZERO. Even if you are a keyboard user, the keyboard controls are adjusting a virtual throttle axis that must be returned to zero before the throttle step position can be adjusted. Use the controls indicator to move the red "ghost" throttle to zero before adjusting the throttle step position.
- Ground steering is accomplished by differential braking. There is no nosewheel steering. The nosewheel caster position is visible on the controls indicator. If you don't have rudder pedals, or are struggling with your keybinds, try the Simple Braking (Rudder Assisted) option in the DCS Special Menu for the A-4E-C, or try assigning a modifier to your rudder axis to utilize the Wheelbrake Differential (Single-Axis) input.

### Multiplayer Troubleshooting

- A DCS standalone server hosting missions with the A-4E-C must have the A-4E-C module installed.
- A server can host players who do not have the A-4E-C module installed on missions that feature it, you will need to be ready to get a little hands-on with your mission files. The Mission Editor dictates that any mission with an A4-E-C in it requires the module (just as it would any other aircraft), and it's `.miz` mission files are, in fact, `.zip` files.
- Make a copy of your `.miz` file, and rename it with a `.zip` file extension, and unzip it.
- Inside, you will find a `mission` file (no extension). Open this file in your text editor of choice (Notepad works just fine), and search for `requiredModules`. Remove the A-4E-C's entry, as shown in this example:

```
["requiredModules"] =
{
     ["A-4E-C"] = "A-4E-C",
}
```

- Once you have completed the edit, save the `mission` file, and re-create a new `.zip` (carefully maintaining proper folder structure, *of course*). Rename your modified mission `.zip` back to a DCS `.miz` file extension instead.
- Finally, test your altered mission by yourself or with a friend to ensure it loads properly, and that clients are able to load into the mission or server without the A4-E-C installed. In this instance, DCS will display any A4-E-C units as an untextured Su-27. Players without the module cannot take control of unit, just as if they did not own any other DCS module in a multiplayer mission.

## Frequently Asked Questions

### Q: Is it really free?

**Yes**! The A-4E-C will remain forever free!

### Q: Are there any plans to obtain the Eagle Dynamics SDK, make the module official, or make the module a part of the default DCS install package?

**No**, the A-4E-C will continue on as a free and open-source resource anyone can download and install to enjoy.

### Q: Can I donate to the A-4E-C project?

**No**, we cannot accept donations, but we appreciate your words of support! There are so many good causes out there. Consider donating to one of those instead!

### Q: Can I get involved with the A-4E-C project?

**Yes**! First, join the [Community A-4E-C Discord server](https://discord.gg/tQZbkTQ) and introduce yourself! We can always use a hand from game artists, programmers or reliable testers as we continue to move the project forward. If you think you have something to contribute, don't hesitate to reach out in the chat.

### Q: Are there manuals or tutorials?

**Yes**! Locating the NATOPS manual for an A-4E/F is the gold standard for understanding this aircraft, but there is a lot of helpful guidance in the included kneeboard manual. To access the manual:

- Once inside the cockpit, open the kneeboard by pressing `RSHIFT+K`
- Read the PDF manual in `%HOMEPATH%\Saved Games\DCS\Mods\aircraft\A-4E-C\Docs`

The [Community A-4E-C Discord server](https://discord.gg/tQZbkTQ) contains a video "hall of fame" featuring high-quality, up-to-date tutorials for all major systems by some of the Community's finest members. Users have also provided manuals in French and Spanish on the discord.

### Q: Is there a paint kit I can use to create my own A-4E-C liveries?

**Yes**! This [A-4E-C Paintkit](https://drive.google.com/open?id=19w_bD8xHJiZpAi1JbA2xyPDJpl9dje-4) includes the aircraft's top, bottom and fuel tanks. See the included liveries for helpful examples setting up your *description.lua* files.

- Liveries created for versions of the A-4E-C prior to 2.0 must update the material names in their *description.lua*. You can use the included `description.lua` files to update
- Install original or downloaded liveries just as you would for any other module, in `%HOMEPATH%\Saved Games\DCS\Liveries\A-4E-C`
- ***Never put your hard work at risk by installing liveries to the module's files!***

### Q: Can I fly the A-4E-C as a tanker?

No.

### Q: Will guided weapons like AGM-12 Bullpup or AGM-62 Walleye be added?

No.

### Q: Why doesn't the A-4E-C have a nosewheel steering button?

There is insufficient evidence to suggest that the A-4E had NWS. According to our research, the revisions and reworks relating to the NWS were applied only to -F models. Leaning to use differential braking takes a little time and effort, but it's a worthwhile skill to develop!

### Q: Are there any plans to simulate other variants or later models of the A-4?

No.

### Q: Why doesn't the A-4E-C work with my favorite mission or multiplayer scripting system?

Some scripts or other utilities need to be informed of the A-4E-C's existence or other specificities in order to accommodate it. If you know of a mod or script that should accommodate it, be sure to let the author know!

### Q: What's the theme song in the DCS main menu?

*Crow*, by [Eric Haugen](https://erichaugen.bandcamp.com/releases)
