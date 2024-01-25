# qqX

## Safe & Powerful text based Quickemu Virtual Machine Manager

Release 1.5.02 now has several new features and is running very smoothly.

- Refactored code is now more small screen friendly.

- VM selector shows if the distro is live boot or installed.

- Quickget interface gives alphabetical zooming into list sections.

- GL graphics can be toggled on/off as required. Handy for basic distros.

- Qemu messages can be suppressed on a per VM basis.

- See screenshots below.

The installer script will update older settings files with the new feature options.

- Use the Github **code/clone** button for the very latest tweaks & bug fixes (if needed).

- The program's built-in downloader will neatly place releases into their own special sub-folder.

### quickemu quickget X terminal project

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

Worry not if [quickgui](https://github.com/quickemu-project/quickgui) is already installed on your system ... qqX is fully compatible and you can easily switch between the two.

### Why the text interface?

Less is more:

By using the same, simple and well-known scripting language that is used by quickemu, qqX is able to achieve complete quickemu script absorption and modding. qqX goes beyond being a simple front-end that is restricted to the basic quickemu API.

Anything within quickemu can be easily pulled, shaped and improved. There is no needed to wait for official bug fixes to make their way through the system either. Any new input from the quickemu community activity can be directly accessed and put to work.

Confident Linux users should quickly find themselves at home.

### Work continues

Release 1.1.01 improved the front end machine selector & makes clearer folder organisation:

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

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

Quick Get multi distro menu:

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

Easy process controlled, progress reporting, distro downloads. Time reporting on zsync development iso's.  

- Clear fully annotated and Shellcheck linted scripting

- Extra process logging and diagnostics

- Full MSRS controls.

- Guided settings editor and auto-update checker

## How to Install

qqX will work quite happily alongside quickgui or quickemu shortcuts. But these are not necessary.

- Start by installing a full normal quickemu setup, if you don't already have a one, complete with all its components and all its dependencies, as in the instructions on the quickemu-project pages. <https://github.com/quickemu-project/quickemu>
  
  You must be able to type `quickemu` at a command prompt and get the quickemu usage screen.

- The latest qqX release is available [here](https://github.com/TuxVinyards/qqX/releases/latest) but it is probably best to make your first download via the **code/clone** button. Also use the Github clone button for the very latest tweaks and bug fixes.

  No other software, support structures or dependancies are needed.

- Extract the files & run the installer, usually right click, then run as program, or similar.

  Further notes are in the installer script itself. Users of Non Filesystem Hierarchy Standard OS's such as NixOS, in particular, should read these & the notes to [#1](https://github.com/TuxVinyards/qqX/issues/1) raised by @flexiondotorg

The installer does require a default VM folder:

- If you have existing *quickemu* virtual machines, start qqX and edit the settings file to point to where they are.

  ![copy location](https://github.com/TuxVinyards/qqX/assets/3956806/13ca993f-34aa-477a-878c-b859e5725c97)

- 'VMQs' will be created in your Home folder, next to Downloads & Videos, if requested.

- The default folder may be moved or renamed using your file manager. Start qqX and edit the settings to point to it.

- If this is a new setup, installing a basic Linux distro, one that you are familiar with perhaps, will tell you if your setup is okay.

When you know that everything is working correctly, you can start exploring ...

- An auto-detector will tell you when new qqX releases are available.

- The qqX installer can be used to update, reinstall, uninstall or reconfigure.

### Installation Tips

You can also open a terminal in the release folder & type `./qqX_setup_and_install`  Note the front `./`  Also note the file should already have execution permissions set. If not, use the right click file properties dialog to set them.

If you have downloaded both named files from the release tab, you can check the download by opening a terminal in the release's download folder and typing `sha256sum -c qqX-` "tab-key" `.s` "tab-key".

All folders can be easily moved around, but make sure that they have their .conf file next to them.

Multiple folders can help organise your distros. You can edit which VMs to show first in the general settings.

If you you are finding the interface a bit cramped, re-run the installer making sure to run the desktop part, rather than skipping, will allow you to tweak the terminal size. Remember of course that terminal window sizing is also affected by the (monospaced) font size. For fonts you may need to see your host distro control panel.

Please report any unnoticed errors. Also any difficulties you may have encountered. By using this software you become a valued member of the community and can help make this software better for others.

### Updating

Make sure to use the installer script so that new features get added to your settings file.

The main settings file has an option for placing updates in a custom folder, instead of the usual 'Downloads' one ...

All locations and preferences will be kept.

## Release notes

Testing has been carried out on a variety of mainstream distros.

All scripts have been carefully Shellcheck linted & have full error handling routines.

qqX always makes backups, as is *standard good practice* with *any* software.

### Changes

Other than in the news section:

There have been a few minor point releases to improve installation on non-standard systems.  

Handling of the new 3 dot quickemu release number has been sorted.

Running of quickget when a zsync live distro had been previously selected has been fixed.

Updates are now tidied into their own specific folders

Tune up auto guidance has been improved.

Qemu-img changing its disksize reporting has been sorted.

Creation of first time snapshots has now been fixed.  

Same with no-start new distros from the config wizard not adding 'G' to the ram= line.  

The way qqX picks up the settings file has been changed to make it easier for forks and branches to be tested and developed. :rocket:

New release 1.4.1 :christmas_tree: had lots of minor improvements plus introduced @zen0bit's URL checking. There was also a neat no-hang browser for opening for OS Home Pages and several under the hood changes in readiness for release 1.5 in the new year.

Release 1.4.5 was semi interim to 1.5.  As previously, it had yet more improvements but several small new features also made their way in, hence the number jump.

Of major importance were two hot fixes for QEMU issues.  One is 'hpet' deprecated code warning. The other is a fix for the recent and recurring 'smartcard problem' [#888](https://github.com/quickemu-project/quickemu/issues/888) and [#717](https://github.com/quickemu-project/quickemu/issues/717) that can affect some distros. Both of these fixes can be toggled from the main settings menu.

Minor pull requests are welcome, as are issues. If qqX is not working, then say so.

### Next release

Work has been focusing on being able to select different qemu machines, set individual custom quickemu scripts and set detailed vm specific configurations.

The ability to have on the fly switching from x86 to, for example aarch64 raspi3b, and others is workable but simpler methods are required, so that we don't take things outside the scope of the project.

Several spin off features are now being backported instead.

A version 2 with machine swaps is being temporarily moved to the back burner until the backporting is complete.

Note the disk health checker doing its thing, in the version 2 snap below.  Clusters repaired too ...  👍

![dev work and disk error alert](https://github.com/TuxVinyards/qqX/assets/3956806/20262c87-83eb-481c-a6f1-a50cd2a0c19b)

Being able to autoinstall from any given random non-quickget ISO is on the wish list.

Conversion between gnome boxes and quickemu is currently on the the todo list for version 2.2 (?)

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
