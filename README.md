# qqX  - quickemu quickget X terminal project

## Latest release 1.8.07

Adds new built-ins and consolidates the raft of tweaks and adjustments to handle all the new Quickemu code

[MacOS](https://github.com/TuxVinyards/qqX/wiki/Mac-OS) is now much faster and much improved too. Both in qqX and in with Quickemu.

Lots of details in the [Wiki](https://github.com/TuxVinyards/qqX/wiki) pages ...

## A Safe and Powerful  Virtual Machine Manager

- Full process & version controlled wrapping of both Quickemu & Quickget

- Desktop Integrated. Works safely alongside other existing GUI installations

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Text based interface for easy [translation](https://github.com/TuxVinyards/qqX/wiki/Translation)

## Why quickemu?

[Quickemu](https://github.com/quickemu-project/quickemu) is a _simply built_ front end for Qemu / KVM  

- It has an active community and is the only virtual machine manager that makes easy work of Mac and Windows.

Developers are now moving to [QEMU](https://qemu.readthedocs.io)

- Quickemu is not like Qemu front-ends based on LibVirt, which can often be quite abstract and complex.

## Why qqX?

qqX goes far beyond the quickemu API

- A full menu system  offers lots more power and functions.

- The easy [installation](https://github.com/TuxVinyards/qqX#how-to-install) needs no additional software or dependencies.

- It has improved display modes, utilities, optimizers and tools.

- qqX is fully compatible with the basic stop / go of [quickgui](https://github.com/quickemu-project/quickgui)

### Hybrid interface. Part text, part mouse

_Less can be more_.

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

Easy _install the latest_ and greatest.

![qqX-mouse-click-iso](https://github.com/TuxVinyards/qqX/assets/3956806/ae6c9fe1-0c46-4e05-b75a-b6964f35bad2)

_No need to wait_ for Quickget to add in the distros or releases that you want.

![qqX-mouse-conf-open](https://github.com/TuxVinyards/qqX/assets/3956806/76a2431b-0573-4fb7-961b-3aa048ea2ca2)

Start specific VM's straight from the folder

### Get the latest fixes

No need to wait for official bug fixes to make their way through the system either. Any new input from the quickemu community activity can be directly accessed and put to work.

Confident Linux users should quickly find themselves at home.

## Screenshots and features

Release 1.1.03 improved the _main menu_ & added a gtk display option, while 1.5.02 now has GL toggle:

![ubuntu-qqX-zsync](https://github.com/TuxVinyards/qqX/assets/3956806/c3104e5d-c008-4dbc-9666-42d13d2af357)

Release 1.5.02 added _alphabetical zooming_ into list sections for the Quick Get multi distro menu:

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

Release 1.7.01 added a choice of 5 _menu styles_ and of  [Custom Menus](https://github.com/TuxVinyards/qqX/wiki/Custom-Menus) :rocket:

![vm-small-d](https://github.com/TuxVinyards/qqX/assets/3956806/1a17b7d7-d6e3-471a-a934-e3530f6c9b17)

Whilst release 1.7.03 built on the earlier NEW INTERFACE FEATURES with

- A _handy distro rename function_ to help with upgrades

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

- If you don't already have a standard Quickemu setup, start by installing that, complete with all its components and all its dependencies, as in the instructions on the [quickemu-project pages](https://github.com/quickemu-project/quickemu) .
  
  You should be able to type `quickemu` at a command prompt and get the quickemu usage screen but from version 1.8 this is not essential.

  Manual installation of Quickemu to 'PATH' as in the case of some Host distros such as Fedora may now be omitted.

- Download qqX. The latest release is available [here](https://github.com/TuxVinyards/qqX/releases/latest). You can also make your first download via the **code/clone** button. The 'dev' branch may be newer and may have the very latest tweaks and bug fixes too ...

  No other software, support structures or dependencies are needed.

See the installer [Wiki](https://github.com/TuxVinyards/qqX/wiki) for more details

## FAQs and Help

Lots available at the qqX wiki pages [here](https://github.com/TuxVinyards/qqX/wiki/FAQs-and-Help)

And the Quickemu general forum and chat is available at <https://discord.gg/sNmz3uw>

## Release notes

Testing has been carried out on a variety of mainstream distros.

All scripts have been carefully Shellcheck linted & have full error handling routines.

qqX always makes backups, as is _standard good practice_ with _any_ software.

See [FreeBird](https://github.com/TuxVinyards/qqX/wiki/FreeBird) for details on the built-ins

See [Change Log](https://github.com/TuxVinyards/qqX/wiki/Change-Log) for a history synopsis

## Why Bash?

Quickemu uses simple Bash scripts. Much easier for community contributions. Much easier to edit and easy to fix.

Any confident Linux user should find it relatively easy to make simple edits.

Learning Bash, or improving your knowledge of it, is always time well spent. Bash is a flexible language of which all Linux users should know at least a little.

### Keep it Simple and Straight forward

qqX uses the same well-known scripting language that is used by quickemu. Anything can be easily taken, shaped and improved.

There are none of steep learning curves that are often involved with GUI's or compiled low level languages such as Rust or C.

The qqX coding style is clear and annotated sufficiently for newcomers to find their feet.

Even with newer and initially simple LibVirt front-ends, like Gnome Boxes for example, doing something basic like moving the VM folder contains a whole learning curve. Forget anything much [more](https://gitlab.gnome.org/GNOME/gnome-boxes/-/tree/main/src?ref_type=heads).

## Development and Roadmap

See the specific [wiki](https://github.com/TuxVinyards/qqX/wiki/Development) for more details

## why 'X' ?

More technically speaking qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'

But traditionally Linux uses the X window system from X.org, so 'X term' often gets used as shorthand ...

<https://en.wikipedia.org/wiki/X_Window_System>

<https://en.wikipedia.org/wiki/Wayland_(protocol)>
