# qqX  - quickemu quickget X terminal project

- Create an easy to build collection of distros and desktops for testing, using and evaluating

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Adds fixes, tools and general improvements to the [Quickemu](https://github.com/quickemu-project/quickemu) system

- Allows the easy running of Linux, Windows, MacOS, etc with [Qemu / KVM](https://qemu.readthedocs.io)

- Offers a complete menu system within a unique hybrid interface

- Is more up-to-date and easier to mod than Gnome Boxes or VirtualBox

- Much easier than the complex Qemu front-ends based on LibVirt.

- And has an easy [installation](#how-to-install)

## [Latest release 1.12.0](https://github.com/TuxVinyards/qqX/releases/latest)

Building on 1.11.0's  large code update and new feature   _mounting of qcow2 drives in a file manager,_

1.12.0 now adds storage maintence tools

- collection size analysis

- individual disk disparity checks

- new utilities interface

Add to this

- Stop, start resume for downloads. Even with overnight pauses.

- And an updated 'daily-live' synchronizer with new release alerts

Plus improvements for Linux mint and the now usual collection of fixes for quickget ....

More in the [release notes](#release-notes) and wiki pages

### Launch from the Linux desktop or from the command line

_No need to wait_ for Quickget to add in the distros or releases that you want.

- Download, right click and install

![qqX-mouse-click-iso](https://github.com/TuxVinyards/qqX/assets/3956806/ae6c9fe1-0c46-4e05-b75a-b6964f35bad2)

- Or at the terminal, simply `qqX /path/distro.iso`

### Search the distro lists with _alphabetical zooming_

- Simple list browse, download, and organise countless distros

- Includes distro homepage browser, link checker and download size reportage

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

### Simple and Straightforward

- Clear to read display modes, utilities, optimizers and tools

- Choice of Custom Menus or 5 built-in _menu styles_

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

- Always up-to-date text [translation](https://github.com/TuxVinyards/qqX/wiki/Translation)

### Get the latest fixes

No need to wait for Quickemu bug fixes to make their way through the system either.

- Built-in code releases ensure that any new input from the quickemu community can be quickly put to work.

### Start the _main menu_ via the desktop or command line

![ubuntu-qqX-zsync](https://github.com/TuxVinyards/qqX/assets/3956806/c3104e5d-c008-4dbc-9666-42d13d2af357)

- For tiling VM's simply type `qqX` at the terminal

### Or start specific VM's straight from the filemanager

![qqX-mouse-conf-open](https://github.com/TuxVinyards/qqX/assets/3956806/76a2431b-0573-4fb7-961b-3aa048ea2ca2)

### Range of utilities and functions

- Qcow2 repair, resize and diagnostics

- Boot manager and ISO boot selector

- Backups and snapshot management

- Controls for Secondary storage
  
- A configuration tune-up wizard

- Custom Qemu boot parameters tools

- Tools to run [Arm64, Risc-V +](https://github.com/TuxVinyards/qqX/wiki/Custom-Machine-Types)

- Distro rename and move utility

- Extended controls for screen size

- Days count on 'daily-live' ISO's

![Screenshot at 2023-02-22 12-59-04-1920](https://user-images.githubusercontent.com/3956806/220619057-f63883d2-4d0d-4130-94e1-d444f1567be4.jpg)

## How to Install

For standard Linux, most users will only need to install `qemu` `spice-gtk` and `qqX`

- Some distro versions may need `curl` `7z` `jq` `bc` and possibly `xrandr`

- The qqX latest release is available [here](https://github.com/TuxVinyards/qqX/releases/latest)

That's it.

- Un-installer included .....

Start from scratch. Or safely test out the qqX difference on your existing VM's.

- Quickemu and Quickgui may be installed but are _not essential_.

- Full installer details in the [wiki](https://github.com/TuxVinyards/qqX/wiki) pages

## Release notes

1.11 was a large code update with lots of new features and Quickemu improvements

@ Nov 27th Beta 1.11.0.2

- New feature _mounting of qcow2 drives in a file manager_ ....
- added several quickget distro updates
- improved vm selector transfer speed
- further improved terminal handling on Qt based desktops, i3 and gnome3

@ Dec 23  Release 1.11.02

- The fix for Windows downloads, recently pushed to Quickemu via Pete Batard's work at [Fido](https://github.com/pbatard/Fido/issues/98)
has now been merged

- The updater and installer has been adjusted and is generally improved. Direct downloads will not be affected but depending on your current updater version you may need to navigate to the download folder using your file manager and run the installer from there until the changes work through system.

@ Dec 31  Release 1.11.03

- fix for Quickget hanging on URL checks when server or internet is slow

- also fixed issue where quickget occasionally outputs multiline release and edition data

- updated FreeSpirit to latest Quickemu 4.9.7/8  > adds proxmox and a couple of other items not in 1.11.02

@ Jan 6 Release 1.11.04

- added several UX adjustments and general polish

- and a new [branch](https://github.com/TuxVinyards/qqX/tree/quickget-distro-fixes-2025) now contains qqX _exclusive fixes_ for multiple distro downloads

### New Release

@ Feb 23 [1.12.0](https://github.com/TuxVinyards/qqX/releases/latest) now> adds storage maintence tools

- collection size analysis

- individual disk disparity checks

- new utilities interface

Add to this

- Stop, start resume for downloads. Even with overnight pauses.

- And an updated 'daily-live' synchronizer with new release alerts

Plus improvements for Linux mint and the now usual collection of fixes for quickget ....

- moves latest FreeSpirit to FreeBird, following testing

## Reliability

- All scripts are carefully Shellcheck linted & have full error handling routines.

- qqX always makes backups, as is _standard good practice_ with _any_ software.

## Fixes for Quickemu

- Available via qqX's [FreeBird](https://github.com/TuxVinyards/qqX/wiki/FreeBird) or FreeSpirit or in the qqX code itself

- Fixes problems causing Intel processors to run MacOS very slowly.

- Fixes the problem where telescoped/nested VM grind to a halt.

- Windows [language fixes](https://github.com/quickemu-project/quickemu/issues/1113) mean that all the downloads work, not just English

- The use of 'floatversion' allows qqX [_exclusive fixes_](https://github.com/TuxVinyards/qqX/wiki/FreeBird#exclusive-quickget-fixes) for multiple distro downloads not available in Quickemu

## FAQs and Help

- Lots of _Quickemu Help_ available in the [qqX wiki pages](https://github.com/TuxVinyards/qqX/wiki/FAQs-and-Help) too, not just qqX

- Full  Quickemu [MacOS installation guide](https://github.com/TuxVinyards/qqX/wiki/Mac-OS) and walk through

- Qemu / qqX  guide to disk resizing and [disk maintenance](https://github.com/TuxVinyards/qqX/wiki/Disks-and-Resizing)

- And more ...

Also try the Quickemu forum at <https://discord.gg/sNmz3uw>

## Why Bash?

Bash, or similar, is automatically there on the Linux command line. Most users already know or can understand at least a little of it.

- Improving your knowledge of Bash is always time well spent.

### Keeping it Simple

- The qqX coding is clear and annotated sufficiently for newcomers to find their feet.

Quickemu currently uses simple Bash scripts. QEMU / KVM does all the heavy lifting.

- Much easier for community contributions. Much easier to edit and easy to fix.

qqX uses a more modern writing style but is much the the same.

- Anything in quickemu can be easily modded, shaped and improved.

### ... and Straightforward

There are none of the complexities that LibVirt creates by using only machine readable configurations.

And none of steep learning curves that come with languages such as Rust, C or Vala.

- Even seemingly simple LibVirt front-ends like Gnome Boxes can contain whole learning curves for the most basic of things, like moving the default VM folder for example.  Forget anything [more](https://gitlab.gnome.org/GNOME/gnome-boxes/-/tree/main/src?ref_type=heads)

## Relationship with Quickemu

qqX should be seen as complementary to Quickemu and as something to improve the Quickemu user experience.

That said, we do seem to be at a point where qqX is becoming an increasingly separate project.

Lack of upstream maintenance and creative differences managed to form [several growing rifts](https://github.com/orgs/quickemu-project/discussions/925) within the Quickemu project during 2024 and in June I added to the growing count of developers who had decided to walk away.

- An increasing number of fixes for Quickemu are having to be added downstream

- Lots of fixes are using separate qqX licensed code

I would like to see an improvement in relationships, so that more people could benefit from the work being done here.

At the beginning of 2025, reinstating the [qqX listing](https://github.com/TuxVinyards/qqX/wiki/FreeBird#creative-differences) on the Quickemu wiki pages would be a good move.

While an analogy could be Ubuntu not promoting derivatives like Linux Mint and Debian not promoting Ubuntu, this doesn't mean that we  have to do the same.

- See [FreeBird](https://github.com/TuxVinyards/qqX/wiki/FreeBird) wiki page for details on the built-ins

## Development and Roadmap

See the specific [wiki](https://github.com/TuxVinyards/qqX/wiki/Development) for _more details_ and for _what's happening_ in future releases

## Contributions

At mid Jan 2025, as [here,](https://github.com/TuxVinyards/qqX/wiki/FreeBird#exclusive-quickget-fixes) there are still quite a few places in Quickget where snippets of static code could do with the addition of [floatversion](https://github.com/TuxVinyards/floatversion) tweaks.

If anyone wants to pick those up and add them to the [latest freespirit](https://github.com/TuxVinyards/quickemu/branches) branch while I am focussing on the `dev-next` branch, that would be useful.

## Why the Vinyards?

I live in a wine growing region of Italy, in a castled village dating from the 1300's

For me, qqX is something to do when it's too hot or it's raining and I can't be outside.
So, Linux development amongst the Vinyards, with the Olde English spelling of " Vine Yards " to match

1533 (1651 pub.), Henry Cornelius Agrippa, De Occulta Philosophia:
> therefore they who are more religiously and holily instructed,
neither set a tree nor plant their _**vinyard**_, nor undertake any mean work without divine invocation

## why 'X' ?

Traditionally Linux has used the X window system from X.org and classically the 'Xterm' command line interface.

- <https://en.wikipedia.org/wiki/X_Window_System>

- <https://en.wikipedia.org/wiki/Wayland_(protocol)>

Technically speaking, qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'
