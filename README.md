# qqX  - quickemu quickget X terminal project

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Adds fixes, tools and general improvements to the [Quickemu](https://github.com/quickemu-project/quickemu) system

- for the easy running of Linux, Windows, MacOS, etc with [Qemu / KVM](https://qemu.readthedocs.io)

- Offers a complete menu system within a unique hybrid interface

- More up-to-date and easier to mod than Gnome Boxes

- Much easier than the complex Qemu front-ends based on LibVirt.

- Easy [installation](#how-to-install)

## [Latest release 1.11.02](https://github.com/TuxVinyards/qqX/releases/latest)

Another large code update with lots of new features and Quickemu improvements.

- new feature allows  _mounting of qcow2 drives in a file manager_

- adds fixes for Arch hosts EFI and for Windows downloads

- extended testing includes tiling WM's and all major desktops

- adds new handling routines for KDE6, XFCE, LXQT and Gnome3

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

- Multiple display modes, utilities, optimizers and tools

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

- Backups and snapshot management

- Controls for Secondary storage
  
- Configuration tune-up wizard

- Qcow2 repair, resize and diagnostics

- Boot manager and ISO boot selector

- Custom boot parameters and the ability to run [Arm64, Risc-V +](https://github.com/TuxVinyards/qqX/wiki/Custom-Machine-Types)

- .conf updater for rename and move

- Controls for screen size and days count on 'daily-live' ISO's

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

@ Nov 27th Beta 1.11.0.2

- New feature _mounting of qcow2 drives in a file manager_ ....

- adds several quickget distro updates

- adds a fix for Arch hosts EFI

- adds a new version manager and checker
  
- adds some improved menus and menu sub-features

- improves vm selector transfer speed

- further improves terminal handling on Qt based desktops

- plus tweaks for i3 and gnome3

- adds a fix for Arch hosts EFI

@ Dec 23  Release [1.11.02](https://github.com/TuxVinyards/qqX/releases/latest)

- Extensive testing has now been completed, including in a wide range of tiling window managers

- The fix for Windows downloads, recently pushed to Quickemu via Pete Batard's work at [Fido](https://github.com/pbatard/Fido/issues/98)
has now been merged

- The updater and installer has been adjusted and is generally improved. Direct downloads will not be affected but depending on your current updater version you may need to navigate to the download folder using your file manager and run the installer from there until the changes work through system.

Enjoy the end of year festivities :christmas_tree:

### Reliability

- Testing is always carried out on a variety of mainstream distros before release. (more so on 1.10)

- All scripts are carefully Shellcheck linted & have full error handling routines.

- qqX always makes backups, as is _standard good practice_ with _any_ software.

### Fixes for Quickemu

- Available via qqX's FreeBird or FreeSpirit or in the qqX code itself

- Fixes problems causing Intel processors to run MacOS very slowly.

- Fixes the problem where telescoped/nested VM grind to a halt.

- Windows [language fixes](https://github.com/quickemu-project/quickemu/issues/1113) mean that all the downloads work, not just English

- And qqX's config autotune fixes Windows boot issue [#1387](https://github.com/quickemu-project/quickemu/issues/1387#top)

See [FreeBird](https://github.com/TuxVinyards/qqX/wiki/FreeBird) wiki page for details on the built-ins, or [change log](https://github.com/TuxVinyards/qqX/wiki/Change-Log) for a history synopsis

### FAQs and Help

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

## Development and Roadmap

See the specific [wiki](https://github.com/TuxVinyards/qqX/wiki/Development) for _more details_ and for _what's happening_ in future releases

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
