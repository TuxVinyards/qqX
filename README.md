# qqX

## " quickemu quickget X terminal project "

Release 1.7.03 builds on the earlier NEW INTERFACE FEATURES and point release bug fixes

- now adds a handy distro rename function to take the errors and tedium from .conf edits when upgrading to new releases
- also adds detection improvements for the Gnome 45 text editor and a few minor general tweaks

Lots of details in the new [Wiki](https://github.com/TuxVinyards/qqX/wiki) pages and in the adjusted main readme.

### 1.8.02  - Hot Fixes for the pending new quickemu release

- This is the new stable branch.  [Download this](https://github.com/TuxVinyards/qqX/tree/1.8.02) in preference.

- Now features quickemu builtins to give much greater control.

- Maintains quickemu 4.9.2 but gives you the [new Quickemu code,](https://github.com/TuxVinyards/qqX/wiki/FreeBird)  as of Apr 25, which people are starting to download and use.

- The Quickemu CLI and API are basically in place. There are still a few problems to sort with Windows and language support but it [generally works](https://github.com/quickemu-project/quickemu/issues/1113)  for international English. MacOS Sonoma can now be downloaded, with a bit of patience.

- Testing for qqX has carried out so far on Fedora 40, Arch and different Ubuntu flavors.

- Fixes have been made for spidering of home pages and reporting of updates. This version should move to release shortly.

## Quickemu Virtual Machine Manager - A Safe and Powerful TUI

- Full process & version controlled wrapping of both Quickemu & Quickget

- Desktop Integrated. Works safely alongside other existing GUI installations

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Text based interface for easy [translation](https://github.com/TuxVinyards/qqX/wiki/Translation)

## Why quickemu?

[Quickemu](https://github.com/quickemu-project/quickemu) is simply built and easy to use.

It has an active community and is the only virtual machine manager that makes easy work of running Microsoft Windows.

VirtualBox was good in its day .... developers are now moving to [QEMU](https://qemu.readthedocs.io)  

Unfortunately, Qemu front-ends are often enterprise orientated and based on LibVirt, which can be quite abstract and complex.

And even beneath Gnome Boxes' initially simple interface, for example, something basic like moving the VM folder contains a whole learning curve. Forget anything [more](https://gitlab.gnome.org/GNOME/gnome-boxes/-/tree/main/src?ref_type=heads) unless you wish to become an expert in xml, gnome3 & vala

Quickemu, on the other hand, is a simple and capable Bash script. Much easier for community contributions. Much easier to edit and easy to fix.

## Why qqX?

qqX goes far beyond a front-end restricted to the basic quickemu API

- A full menu system that improves on the traditional quickemu interfaces

- Lots of power and functions. Even more than quickemu.

- An easy installation with no additional software or dependencies required.

Quickemu only works on the command line and quickgui is very basic.

- qqX is fully compatible with [quickgui](https://github.com/quickemu-project/quickgui) if it is already installed on your system.
  
Using qqX will power up existing VM's with improved display modes, utilities, optimizers and tools.

### Not just a text interface

Less can be more.

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

qqX uses the same well-known scripting language that is used by quickemu.

And anything within quickemu can be easily taken, shaped and improved.

### Install the latest ISO's at the click of a mouse

![right-click-iso](https://github.com/TuxVinyards/qqX/assets/3956806/23dd984c-8119-4d8a-b486-c26ac7bf21bb)

No need to wait for Quickget to add in the distros or releases that you want.

### Get the latest fixes too

There is no need to wait for official bug fixes to make their way through the system either. Any new input from the quickemu community activity can be directly accessed and put to work.

Confident Linux users should quickly find themselves at home.

### Work continues

Release 1.1.01 improved the front end machine selector & makes clearer folder organisation:

Release 1.1.03 improved the main menu & added a gtk display option, while 1.5.02 now has GL toggle:

![ubuntu-qqX-zsync](https://github.com/TuxVinyards/qqX/assets/3956806/c3104e5d-c008-4dbc-9666-42d13d2af357)

Release 1.5.02 added alphabetical zooming into list sections for the Quick Get multi distro menu:

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

Release 1.7.01 now has a choice of 5 menu styles and of  [Custom Menus](https://github.com/TuxVinyards/qqX/wiki/Custom-Menus) :rocket:

![vm-small-d](https://github.com/TuxVinyards/qqX/assets/3956806/1a17b7d7-d6e3-471a-a934-e3530f6c9b17)

And 1.6.02 introduced [custom boot parameters](https://github.com/TuxVinyards/qqX/wiki/Custom-Qemu-boot-parameters) and the ability to run [Arm64, Risc-V +](<https://github.com/TuxVinyards/qqX/wiki/Custom-Machine-Types>)

Earlier releases have added:

- Distro homepage browser and link checker
  
- Configuration tune-up wizard

- Screen percentage switching (default & individual)

- Multiple snapshot management, including of shared disks.

- qcow2 repair & resize

- Secondary storage creation

- Progress reporting on distro downloads & zsync iso's.  

- Process logging and diagnostics

![Screenshot at 2023-02-22 12-59-04-1920](https://user-images.githubusercontent.com/3956806/220619057-f63883d2-4d0d-4130-94e1-d444f1567be4.jpg)

## How to Install

qqX will work happily alongside quickgui or any quickemu shortcuts. But these are not necessary.

Start from scratch. Or safely test out the qqX difference on your existing quickgui VM's  

- If you don't already have a standard Quickemu setup, start by installing that, complete with all its components and all its dependencies, as in the instructions on the [quickemu-project pages](https://github.com/quickemu-project/quickemu)
  
  You must be able to type `quickemu` at a command prompt and get the quickemu usage screen.

- Download qqX. The latest release is available [here](https://github.com/TuxVinyards/qqX/releases/latest). You can also download via the **code/clone** button. The 'dev' branch may be newer and may have the very latest tweaks and bug fixes too ...

  No other software, support structures or dependencies are needed.

See the installer [Wiki](https://github.com/TuxVinyards/qqX/wiki) for more details

## FAQs and Help

FAQ: [Wiki](https://github.com/TuxVinyards/qqX/wiki/FAQs-and-Help)

## Release notes

Testing has been carried out on a variety of mainstream distros.

All scripts have been carefully Shellcheck linted & have full error handling routines.

qqX always makes backups, as is *standard good practice* with *any* software.

Release 1.1.05, added an extra layer of qemu-img disk health checks to the disk info function.

![disk error alert crop](https://github.com/TuxVinyards/qqX/assets/3956806/7edf972c-3c18-4f33-8096-2c1cbc5ba4f5)

Feedback, positive or constructive, at <https://discord.gg/sNmz3uw>

## Development

When making clones of the repo to your local machine, you can easily run any new version of qqX directly from the working folder.

See the specific [wiki](https://github.com/TuxVinyards/qqX/wiki/Development) for more details

## Bash

Learning Bash, or improving your knowledge of it, is always time well spent. Bash is a flexible language of which all Linux users should know at least a little. There are none of steep learning curves that are often involved with GUI's

Use of a clear and well annotated qqX coding style means that even Bash novices should be able to find their feet. Any confident Linux user should find it relatively easy to make simple edits.

## why 'X' ?

More technically speaking qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'

But traditionally Linux uses the X window system from X.org, so 'X term' often gets used as shorthand ...

<https://en.wikipedia.org/wiki/X_Window_System>

<https://en.wikipedia.org/wiki/Wayland_(protocol)>
