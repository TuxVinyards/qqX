# qqX  - quickemu quickget X terminal project

- Create an easy to build collection of distros and desktops for testing, using and evaluating

- _Safe, carefully written, well tested and checked_

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Allows the easy running of Linux, Windows, MacOS, etc with [Qemu / KVM](https://qemu.readthedocs.io)

## Basically Better

- Adds [fixes, tools and general improvements](https://tuxvinyards.github.io/qqX/docs/FreeBird) to the popular Quickemu system

- More up-to-date and easier to mod than Gnome Boxes or VirtualBox

- Much easier than the complex Qemu front-ends based on LibVirt.

### Launch from the Linux desktop or from the command line

- Easy to use menu system with unique hybrid interface

## [Latest release 1.13.01](https://github.com/TuxVinyards/qqX/releases/latest)

- Huge new upgrade for QuickGet, fixes, sorts and adds over 25 distros

- Adds a new Quickget filter system

- And adds fixes for qqX right click and Text Editor issues in Gnome

Includes earlier downstream fixes for Quickemu issues:

- Qemu version 10.0.0

- Windows Installer

More in the [release notes](https://tuxvinyards.github.io/qqX/docs/Release-Notes) and qqX pages

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

- Reliable text [translation](https://tuxvinyards.github.io/qqX/docs/Translation) methods.

## The latest updates

[No waiting months](https://github.com/quickemu-project/quickemu/releases) for Quickemu bug fixes and changes

- qqX's built-in code [system](https://tuxvinyards.github.io/qqX/docs/FreeBird) ensures that any new input can be quickly put to work

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

- [Full installer details](https://tuxvinyards.github.io/qqX/docs/Installation) in the qqX pages

## Reliability

- All scripts are carefully Shellcheck linted & have full error handling routines.

- qqX always makes backups, as is _standard good practice_ with _any_ software.

## FAQs and Help

- Lots of _Quickemu Help_ available in the [qqX pages](https://tuxvinyards.github.io/qqX/docs/FAQs-and-Help) too, not just qqX

- Full  Quickemu [MacOS installation guide](https://tuxvinyards.github.io/qqX/docs/Guides/Mac-OS) and [Windows Installer walk-tru](https://tuxvinyards.github.io/qqX/docs/Guides/Windows-OS)

- Qemu / qqX  guide to disk resizing and [disk maintenance](https://tuxvinyards.github.io/qqX/docs/Advanced/Disks-and-Resizing)

- And more ...

Also try the Quickemu forum at <https://discord.gg/sNmz3uw>

## Development and Roadmap

See the specific [dev pages](https://tuxvinyards.github.io/qqX/docs/Advanced/Development) for _more details_ and for _what's happening_ in future releases

## Coding Contributions

If you are more comfortable with older style Bash, this is permitted in the Quickemu scripts

- [Downstream fixes for Quickget](https://tuxvinyards.github.io/qqX/docs/FreeBird#exclusive-quickget-fixes) are always needed

The new Quickget Mods script is an ideal place to start. Located in the FreeSpirit builtins folder ....

Anyone wanting to pick up on those should add them to the latest [dev-next](https://github.com/TuxVinyards/qqX/branches) branch

Also if anyone has used the custom menu feature and wants to share their work, that would be great as well

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
