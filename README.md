# qqX  - quickemu quickget X terminal project

- Create an easy to build collection of distros and desktops for testing, using and evaluating

- _Safe, carefully written, well tested and checked_

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Allows the easy running of Linux, Windows, MacOS, etc with [Qemu / KVM](https://qemu.readthedocs.io)

## Basically Better

- Adds [fixes, tools and general improvements](https://github.com/TuxVinyards/qqX/wiki/FreeBird) to the Quickemu system

- More up-to-date and easier to mod than Gnome Boxes or VirtualBox

- Much easier than the complex Qemu front-ends based on LibVirt.

### Launch from the Linux desktop or from the command line

- Easy to use menu system with unique hybrid interface

## [Latest release 1.12.07](https://github.com/TuxVinyards/qqX/releases/latest)

- Adds several downstream fixes: Solus, Parrot, Sparky

- Adds Nobara and a few UI improvements

Includes earlier downstream fixes for Quickemu issues:

- Qemu version 10.0.0

- Windows Installer

More in the [release notes](#release-notes-and-highlights) and wiki pages

## Ease of the GUI

![qqX-mouse-click-iso](https://github.com/TuxVinyards/qqX/assets/3956806/ae6c9fe1-0c46-4e05-b75a-b6964f35bad2)

- Download, right click and install

## Power and simplicity of the command line

Search the quickget distro list with _alphabetical zooming_

- Simple list browse, download, and organise countless distros

- Includes distro homepage browser, link checker and download size reportage

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

- Or at the terminal, simply `qqX /path/distro.iso`

## Straightforward and easy to work with

- Clear to read display modes, utilities, optimizers and tools

- Easy to fix, mod and customise

- Choice of Custom Menus or 5 built-in _menu styles_

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

- Reliable text [translation](https://github.com/TuxVinyards/qqX/wiki/Translation) methods.

## The latest updates

[No waiting months](https://github.com/quickemu-project/quickemu/releases) for Quickemu bug fixes and changes

- qqX's built-in code [system](https://github.com/TuxVinyards/qqX/wiki/FreeBird) ensures that any new input can be quickly put to work

- Choice of 3 easy-swap _rolling release_ models: Leading Edge, Standard or Slow

## Easy utilities

- Safeguard your machines with easy snapshot management

- Make sure drives are healthy with Qcow2 repair, resize and diagnostics

- Edit machine partitions by booting from maintenance ISO's

- View inside virtual machines using a file manager

![qcow2-disk-utils-qf-1920](https://github.com/user-attachments/assets/3262f7be-ddcb-4b98-b44a-6e75ca82eab0)

- Configuration tune-up wizard

![windows-insider-sdl-1920](https://github.com/user-attachments/assets/c586e2e2-d285-49a2-93c2-2ce506ba2f36)

- And more

## How to Install

For standard Linux, most users will only need to install `qemu` `spice-gtk` and `qqX`

- Some distro versions may need `curl` `7z` `jq` `bc` and possibly `xrandr`

- The qqX latest release is available at [https://github.com/TuxVinyards/qqX/releases/latest](https://github.com/TuxVinyards/qqX/releases/latest)

That's it.

- Built-in updater included .....

Start from scratch. Or safely test out the qqX difference on your existing VM's.

- Fully compatible with Quickemu machines

- Quickemu and Quickgui may be installed but are _not essential_.

- [Full installer details](https://github.com/TuxVinyards/qqX/wiki) in the wiki pages

## Reliability

- All scripts are carefully Shellcheck linted & have full error handling routines.

- qqX always makes backups, as is _standard good practice_ with _any_ software.

## FAQs and Help

- Lots of _Quickemu Help_ available in the [qqX wiki pages](https://github.com/TuxVinyards/qqX/wiki/FAQs-and-Help) too, not just qqX

- Full  Quickemu [MacOS installation guide](https://github.com/TuxVinyards/qqX/wiki/Mac-OS) and [Windows Installer walk-tru](https://github.com/TuxVinyards/qqX/wiki/Windows-OS)

- Qemu / qqX  guide to disk resizing and [disk maintenance](https://github.com/TuxVinyards/qqX/wiki/Disks-and-Resizing)

- And more ...

Also try the Quickemu forum at <https://discord.gg/sNmz3uw>

## Release notes and highlights

### Release 1.11

@ Nov 27th - 1.11.0.2

- New feature [_mounting of qcow2 drives in a file manager_](https://github.com/TuxVinyards/qqX/wiki/Disks-and-Resizing#other-tools)

### Release 1.12

@ Feb 23 - 1.12.0

- Distro storage size analysis and size disparity checks

![new size-ui](https://github.com/user-attachments/assets/0df37ca8-b4c1-4af8-a883-82ef60744649)

- And extended **stop, start and resume** for downloads

![stop-start-resume](https://github.com/user-attachments/assets/d710f47f-a2b9-4bda-beda-5f5290dfad52)

@ March 14 - 1.12.01

- [Downstream fix for the Quickemu Windows Installer issue #1475](https://github.com/quickemu-project/quickemu/issues/1475)

- [Windows Installer walk-tru](https://github.com/TuxVinyards/qqX/wiki/Windows-OS) in the qqX wiki

@ March 28 - 1.12.02

- Distro finder for searching large distro collections

@ April 17 - 1.12.04

- Upgrades [floatversion](https://github.com/TuxVinyards/floatversion) to 1.4.01

And updates Quickget with _downstream_ distro fixes for:

- AntiX
- Freedos
- Garuda
- Kolibri
- Oracle
- Parrot Sec
- PC Linux

@ Apr 25 - 1.12.05

- Adds upstream fix for Bazzite

Plus downsteam fixes for :

- Fedora 42 KDE
- VanillaOS
- VX

@ May 2 - 1.12.06

- Adds fixes for QuickEmu and new Qemu version 10.0.0
- Improves UI for dependency checker

@ May 2 - 1.12.07

- Adds several downstream fixes: Solus, Parrot, Sparky
- Adds Nobara and a few UI improvents

Full details in [releases](https://github.com/TuxVinyards/qqX/releases) and [commits](https://github.com/TuxVinyards/qqX/commits/main/)

## Relationship with Quickemu

Lack of upstream maintenance and creative differences managed to form [several growing rifts](https://github.com/orgs/quickemu-project/discussions/925) within the Quickemu project during 2024 and in June a growing count of developers decided to walk away.

- An increasing number of fixes for Quickemu are now having to be added downstream

- See [FreeBird](https://github.com/TuxVinyards/qqX/wiki/FreeBird) wiki page for details on the built-ins

There needed to be an improvement in relationships, so that more people could benefit from the work being done here.

- Reinstating the [qqX listing](https://github.com/TuxVinyards/qqX/wiki/FreeBird#creative-differences) on the Quickemu wiki pages would have been a good move.

![qqX-on-the-quickemu-wiki](https://github.com/user-attachments/assets/3c11249e-4898-4882-a82e-c460472e8099)

### Competition

qqX was always intended as an extra optional interface for Quickemu. It was never intended to be a competitive project.

However during 2025, the upstream stance hardened further and any [attempts to provide simple help or to address issues within the upstream code base](https://github.com/quickemu-project/quickemu/issues/1660) continued to be misconstrued as competitive attacks. Instead of rifts healing, recent pushes for improvements in relationships have failed abysmally.

Please _be reassured_ that qqX _will continue to support virtual machines_ that have been created via either command line QuickEmu or QuickGUI or vice versa, despite being forced into becoming a competitor.

## Downstream fixes for Quickemu

- Available via qqX's [freebird](https://github.com/TuxVinyards/qqX/wiki/FreeBird) or in the qqX code itself

- Fixes problems causing Intel processors to run MacOS very slowly

- Fixes the problem where telescoped/nested VM grind to a halt

- Windows language fixes mean that [all](https://github.com/quickemu-project/quickemu/issues/1113)  the downloads work, not just English

- Fixes the Quickemu Windows Installer issue [#1475](https://github.com/quickemu-project/quickemu/issues/1475)

- The use of [floatversion](https://github.com/TuxVinyards/floatversion) allows multiple distro downloads not available in Quickemu

- And more

## Why Bash?

### Keeping it Simple

The qqX coding is clear and annotated sufficiently for newcomers to find their feet

- qqX uses a more modern interpretation of Bash than that used in Quickemu

- but anything in quickemu can still be easily modded, shaped and improved

QEMU / KVM does all the heavy lifting

- Much easier for community contributions

- Much easier to edit and easy to fix

### ... and Straightforward

qqX follows quickemu's pattern of using human orientated configuration files

- none of the complexities of only having machine readable configurations, as with LibVirt

Requires no special setup as do languages such as Rust, C or Vala

- no potentially steep [learning](https://gitlab.gnome.org/GNOME/gnome-boxes/-/tree/main/src?ref_type=heads) curves

Bash is automatically there on almost every Linux system, directly on the command line.

- easily integrates with the Linux core utilities and sub-system

- is more performant than basic Posix Shell

Improving your knowledge of Bash is always time well spent

- Most users already know or can understand at least a little of it.

## Development and Roadmap

See the specific [wiki](https://github.com/TuxVinyards/qqX/wiki/Development) for _more details_ and for _what's happening_ in future releases

## Contributions

If you are more comfortable with older style Bash, this is permitted in the Quickemu scripts

- [Downstream fixes for Quickget](https://github.com/TuxVinyards/qqX/wiki/FreeBird#exclusive-quickget-fixes) are always needed

- Quickget could still do with further [floatversion](https://github.com/TuxVinyards/floatversion) tweaks ...

Anyone wanting to pick up on those should add them to the latest [freespirit](https://github.com/TuxVinyards/quickemu/branches) or [dev-next](https://github.com/TuxVinyards/qqX/branches) branch

Also if anyone has used the custom menu feature and wants to share their work, that would be great as well

## Why the Vinyards?

Linux development, with the preferable Olde English spelling, amongst the vineyards

Alex Genovese lives in a wine growing region of Italy, in a castled village dating from the 1300's

"qqX is something to work on when it's too hot or it's raining and I can't be outside"

1533 (1651 pub.), Henry Cornelius Agrippa, De Occulta Philosophia:
> therefore they who are more religiously and holily instructed,
neither set a tree nor plant their _**vinyard**_, nor undertake any mean work without divine invocation

## why 'X' ?

Traditionally Linux has used the X window system from X.org and classically the 'Xterm' command line interface.

- [https://en.wikipedia.org/wiki/X_Window_System](https://en.wikipedia.org/wiki/X_Window_System)

- [https://en.wikipedia.org/wiki/Wayland_(protocol)](https://en.wikipedia.org/wiki/Wayland_\(protocol\))

Technically speaking, qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'
