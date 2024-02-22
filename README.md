# qqX

## " quickemu quickget X terminal project "

1.6.02 introduces a new Custom Boot system that can run Arm64, Risc-V and others.

Plus a couple of UI tweaks and minor bug fixes.

See the new Wiki pages <https://github.com/TuxVinyards/qqX/wiki/Custom-Qemu-boot-parameters>

##  Quickemu Virtual Machine Manager - A Safe and Powerful TUI 

- Full process & version controlled wrapping of both Quickemu & Quickget

- Desktop Integrated. Works safely alongside other existing GUI installations

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

## Why quickemu?

[Quickemu](https://github.com/quickemu-project/quickemu) is simply built and easy to use.

It has an active community and is the only virtual machine manager that makes easy work of running Microsoft Windows.

It's not without its flaws. But its flaws can be fixed and it can be made to work.

VirtualBox was good in its day.  Developers are now moving to QEMU <https://qemu.readthedocs.io>

Gnome Boxes (with QEMU) has a very polished interface. But even something simple like moving the VM folder has a learning curve. Forget anything more complex unless you wish to become an expert in xml, gnome3 & vala : <https://gitlab.gnome.org/GNOME/gnome-boxes/-/tree/main/src?ref_type=heads>

## Why qqX?

qqX offers an alternative menu system that has lots of power and functions. More even than quickemu.

It has an easy installation. No additional software or dependancies are required.

Quickemu works on the command line and traditionally has had a simple menu interface called quickgui.

qqX is fully compatible with [quickgui](https://github.com/quickemu-project/quickgui) if is already installed on your system ...  and you can easily switch between the two.

### Why the text interface?

Less is more:

By using the same, simple and well-known scripting language that is used by quickemu, qqX is able to achieve complete quickemu script absorption and modding.

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

qqX goes far beyond being a simple front-end that is restricted to the basic quickemu API.

Anything within quickemu can be easily pulled, shaped and improved.

There is no needed to wait for official bug fixes to make their way through the system either. Any new input from the quickemu community activity can be directly accessed and put to work.

Confident Linux users should quickly find themselves at home.

### Work continues

Release 1.1.01 improved the front end machine selector & makes clearer folder organisation:

Release 1.1.03 improved the main menu & added a gtk display option, while 1.5.02 now has GL toggle:

![ubuntu-qqX-zsync](https://github.com/TuxVinyards/qqX/assets/3956806/c3104e5d-c008-4dbc-9666-42d13d2af357)

Earlier releases have added:

- qcow2 repair & resize

- configuration tune-up wizard

![Screenshot at 2023-02-22 12-59-04-1920](https://user-images.githubusercontent.com/3956806/220619057-f63883d2-4d0d-4130-94e1-d444f1567be4.jpg)

Release 1.1.05, added an extra layer of qemu-img disk health checks to the disk info function. Picture of it working lower down, in the release notes section.  Disks can go wrong. 👍 Give it a try.

Plus:

- Quick screen percentage switching (default & individual)

- Easy secondary storage creation

- Multiple snapshot management, including of shared disks.  

Release 1.5.02 added alphabetical zooming into list sections for the Quick Get multi distro menu:

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

Easy process controlled, progress reporting, distro downloads. Time reporting on zsync development iso's.  

- Clear fully annotated and Shellcheck linted scripting

- Extra process logging and diagnostics

- Full MSRS controls.

- Guided settings editor and auto-update checker

## How to Install

qqX will work happily alongside quickgui or any quickemu shortcuts. But these are not necessary.

- Start by installing a full normal quickemu setup, if you don't already have a one, complete with all its components and all its dependencies, as in the instructions on the quickemu-project pages. <https://github.com/quickemu-project/quickemu>
  
  You must be able to type `quickemu` at a command prompt and get the quickemu usage screen.

- The latest qqX release is available [here](https://github.com/TuxVinyards/qqX/releases/latest) but it is probably best to make your first download via the **code/clone** button. Also use the Github clone button for the very latest tweaks and bug fixes.

  No other software, support structures or dependancies are needed.

See the Wiki for more details <https://github.com/TuxVinyards/qqX/wiki>

## FAQs and Help

See Wiki <https://github.com/TuxVinyards/qqX/wiki/FAQs-and-Help>

## Release notes

Testing has been carried out on a variety of mainstream distros.

All scripts have been carefully Shellcheck linted & have full error handling routines.

qqX always makes backups, as is *standard good practice* with *any* software.

More details here: <https://github.com/TuxVinyards/qqX/wiki/Change-Log>

Feedback, positive or constructive, at <https://discord.gg/sNmz3uw>

## Development

You can easily run any new version of qqX directly from the working folder when making clones of the repo to your local machine.  By default, this will pick up the main settings file at `~/.qqX` and automatically locate all your current VMs.

qqX has several layers of backup and fail safe, however do backup critical VMs if tinkering with these systems.

You are recommended to place any development changes to the settings file into a single block so that they can be easily pasted back after carrying out release upgrades to your main qqX installation.

Whilst the release installer will automatically backup your settings file, part of the update procedure is the removal of obsolete and unneeded lines. This will cause a temporary removal of any changes that you may have made.

The code has now been refactored to make readability easier on notebooks and smaller height screens. Release 1.5.02, even with its new added features and script, is more compact and around 500 lines shorter ... :rocket:

## Bash

Learning Bash, or improving your knowledge of it, is always time well spent. Bash is a flexible language of which all Linux users should know at least a little. There are none of steep learning curves that are often involved with GUI's

Use of a clear and well annotated qqX coding style means that even Bash novices should be able to find their feet. Any confident Linux user should find it relatively easy to make simple edits.

## why 'X' ?

More technically speaking qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'

But traditionally Linux uses the X window system from X.org, so 'X term' often gets used as shorthand ...

<https://en.wikipedia.org/wiki/X_Window_System>

<https://en.wikipedia.org/wiki/Wayland_(protocol)>
