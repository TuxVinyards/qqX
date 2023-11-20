# qqX

## Safe & Powerful text based Quickemu Virtual Machine Manager

Use the Github **code/clone** button for the latest tweaks & bug fixes ...

The recent bug that stopped the creation of first time snapshots has now been fixed.  The same with the bug in the config wizard not adding 'G' to the ram= line which caused new distros to fail to start in both quickemu & qqX  

Changes to qemu-img and its reporting on disksizes caused a few math headaches. Thats now fixed too.

Release 1.2.01 is a number boost to reflect all the recent tweaks and fixes. 

Release 1.1.05, added an extra layer of qemu-img disk health checks to the disk info function. Disks can go wrong. Picture of it working lower down, in the release notes section 👍 Give it a try.

Your help at making this software better is always appreciated.

### quickemu quickget X terminal project

- Full process & version controlled wrapping of both Quickemu & Quickget

- Desktop Integrated. Works safely alongside other existing GUI installations

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

## Why quickemu?

Quickemu is simply built and easy to use.

It has an active community & is the only virtual machine manager that makes easy work of running Microsoft Windows.

It's not without its flaws. But its flaws can be fixed & it can be made to work.

VirtualBox was good in its day.  Developers are now moving to QEMU <https://qemu.readthedocs.io>

Gnome Boxes (with QEMU) has a wonderfully polished load up interface.  If only qqX looked that good too ... :rofl:  

The problems with Gnome Boxes are the problems. When it's working it's great. But even something simple like moving the VM folder has a learning curve. Forget anything more complex unless you wish to become an expert in xml, gnome3 & vala : <https://gitlab.gnome.org/soneca/gnome-boxes/-/tree/main/src?ref_type=heads>

## Why qqX?

[Quickemu](https://github.com/quickemu-project/quickemu) works on the command line & its menu interface has traditionally been  quickgui.

qqX *now* offers an alternative menu system that has more functions & power. More even than quickemu.

Install qqX on your machine & you can still keep the simplicity of [quickgui](https://github.com/quickemu-project/quickgui) if you want to.

Confident Linux users should quickly find themselves at home with qqX but you can switch between them at will.

### Why the text interface?

Less is more:

By using the same, less sophistcated, simple scripting language as quickemu, we can achieve far easier modding, editing & interaction ...  and thus a much more powerful interface. The qqX project benefits directly from all the quickemu community activity.

### Work continues

Release 1.1.01 improves the front end machine selector & makes clearer folder organisation:

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

Release 1.1.03 adds a few tweaks to the main menu & adds a gtk display option :

![qqX-main-113](https://github.com/TuxVinyards/qqX/assets/3956806/bb5db28d-9105-46e4-9ac2-c6cf4e57a951)

Earlier releases have added:

- qcow2 repair & resize

- configuration tune-up wizard

![Screenshot at 2023-02-22 12-59-04-1920](https://user-images.githubusercontent.com/3956806/220619057-f63883d2-4d0d-4130-94e1-d444f1567be4.jpg)

Plus:

- Quick screen percentage switching (default & individual)

- Easy secondary storage creation

- Multiple snapshot management, including of shared disks.  

Quick Get multi distro menu:

![QGW](https://github.com/TuxVinyards/quickemu-mod/assets/3956806/c948f51a-a954-4180-ba62-1d5045e5f4fc)

Easy process controlled, progress reporting, distro downloads. Time reporting on zsync development iso's.  

- Clear fully annotated & Shellcheck linted scripting

- Extra diagnostics, functions & process logging

- Full MSRS controls.

- Guided settings editor and auto-update checker

## How to Install

qqX will work quite happily alongside quickgui or quickemu shortcuts. But these are not necessary.

- Start by installing a full normal quickemu setup, if you don't already have a one, complete with all its components and all its dependencies, as in the instructions on the quickemu-project pages. <https://github.com/quickemu-project/quickemu>
  
  You must be able to type `quickemu` at a command prompt and get the quickemu usage screen.

- The latest qqX release is available [here](https://github.com/TuxVinyards/qqX/releases/latest) but it is probably best to make your first download via the **clone** button. Also use the Github clone button for the latest bug fixes ....

  Please report unnoticed errors. By using this software YOU become a valued member of the community.

- Extract the files & run the installer, usually right click, then run as program, or similar.

  Further notes are in the installer script itself. Users of Non-Filesystem_Hierarchy_Standard OS's such as NixOS, in particular, should read these & the notes to [#1](https://github.com/TuxVinyards/qqX/issues/1) raised by @flexiondotorg

The installer requires a default VM folder:

- If you have existing virtual machines, start qqX and edit the settings file to point to where they are.

  ![copy location](https://github.com/TuxVinyards/qqX/assets/3956806/13ca993f-34aa-477a-878c-b859e5725c97)

- If this is a new setup, start qqX, check the settings & then install a basic Linux distro, one that you are familiar with perhaps, which will tell you if your setup is okay.

When you know that everything is working correctly, you can start exploring ...

- qqX will auto-detect if new releases are later available & quietly prompt for updates.

- The installer can be used to update, reinstall, uninstall or reconfigure.

### Installation Tips

You can also open a terminal in the release folder & type `./qqX_setup_and_install`  Note the front `./`  Also note the file should already have execution permissions set. If not, use the right click file properties dialog to set them.

If you have downloaded both named files from the release tab, you can check the download by opening a terminal in the release's download folder & typing `sha256sum -c qqX-` "tab-key" `.s` "tab-key".

## Release notes

Now in official release. Testing has been carried out on a variety of mainstream distros.

Both the release candidate & the beta versions have been consistently safe & stable.

All scripts have been carefully Shellcheck linted & have full error handling routines.

qqX always makes backups, as is *standard good practice* with *any* software.

Feedback, positive or constructive, at <https://discord.gg/sNmz3uw>

### Changes

There have been a few minor point releases to improve installation on non-standard systems.  

Release 1.1.04 amends handling of the new 3 dot quickemu release number and corrects the running of quickget when a zsync live distro had been previously selected.

Release 1.1.01 improves the front end machine selector & makes clearer folder organisation.  There are also a few 'under the hood' changes like tidying updates into their own specific folders (takes effect on next update) & improving the tune up auto guidance.

Crucially too, GitHub wise, the way qqX picks up the settings file has been changed. This now makes it much easier for forks and branches to be tested & developed. :rocket:

Minor pull requests are welcome as are issues. If qqX is not working, then say so.

### Next release

Work is now focusing on being able to: select different qemu machines, set individual custom quickemu scripts & set detailed vm specific configurations. This should offer not only a range of VM specfic fixes; we should also be able to achieve on the fly switching from x86 to, for example aarch64 raspi3b, and a host of others.  Expect a 'dev' branch to be released shortly.

But not forgetting some of the new pull requests making their way into quickemu code, like @zen0bit 's for distro homepages  [here](<https://github.com/quickemu-project/quickemu/pull/801#issuecomment-1762671744>)

Note the disk health checker doing its thing, in the snap below.  Clusters repaired too ...  👍

![dev work and disk error alert](https://github.com/TuxVinyards/qqX/assets/3956806/20262c87-83eb-481c-a6f1-a50cd2a0c19b)

## Bash

Learning Bash, or improving your knowledge of it, is always time well spent. Bash is a flexible language of which all Linux users should know at least a little. There are none of steep learning curves that are often involved with GUI's

Use of a clear and well annotated qqX coding style means that even Bash novices should be able to find their feet. Any confident Linux user should find it relatively easy to make simple edits.

## why 'X' ?

More technically speaking qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'

But traditionally Linux uses the X window system from X.org, so 'X term' often gets used as shorthand ...

<https://en.wikipedia.org/wiki/X_Window_System>

<https://en.wikipedia.org/wiki/Wayland_(protocol)>
