# qqX

## Safe & Powerful text based Quickemu Virtual Machine Manager

### quickemu quickget X terminal project

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Desktop Integrated & with added right click qcow2 analysis

- Works safely alongside other existing GUI installations

- Clear fully annotated & Shellcheck linted scripting

- Full process & version controlled wrapping of both Quickemu & Quickget

- Extra diagnostics, functions & process logging

- Guided VM download with configuration tune-up

- Guided settings options with settings editor and auto-update checker

- Quick VM screen percentage switching with both default & individual preset options

- Easy secondary & shared storage creation wizard

- Multiple snapshot management, including of shared disks.  

- Full MSRS controls.

Release 1.0.01 - Now with:

- qcow2 repair & resize

- configuration tune-up wizard
  
![Screenshot at 2023-02-22 12-59-04-1920](https://user-images.githubusercontent.com/3956806/220619057-f63883d2-4d0d-4130-94e1-d444f1567be4.jpg)

![QGW](https://github.com/TuxVinyards/quickemu-mod/assets/3956806/c948f51a-a954-4180-ba62-1d5045e5f4fc)

## Text Interface

qqX belongs to the 'less is more' school of thought:

The GUI can *look* more polished but by using the same simple scripting language as quickemu, we can achieve far easier modding, editing & interaction ...  and thus a much more powerful interface.

There are none of steep learning curves often involved with a GUI, which allows better community involvement.

Bash is a flexible language of which all Linux users should know at least a little. Learning Bash, or improving your knowledge of it, is always time well spent, whilst qqX's use of a clear and well annotated coding style means that even novices should be able to find their feet.

## Install

qqX may be happily installed alongside quickgui or quickemu shortcuts, if present, but these are not necessary.

- Start by installing a full normal quickemu setup, if you don't already have a one, complete with all its components and all its dependencies, as in the instructions on the quickemu-project pages. <https://github.com/quickemu-project/quickemu>
  
  You must be able to type `quickemu` at a command prompt and get the quickemu usage screen.

- Download the latest qqX release [here](https://github.com/TuxVinyards/qqX/releases/latest)

  If you download both named files, you may check the download by opening a terminal in the release's download folder & typing `sha256sum -c qqX-` "tab-key" `.s` "tab-key".

- Extract the files & run the installer, usually right click, then run as program, or similar.

  You can also open a terminal in the release folder & type `./qqX_setup_and_install`  Note the front `./`  The file should already have execution permissions set. If not, use the right click, file properties dialog to set them.

- If you have existing virtual machines, start qqX and edit the settings file to point to where they are.

- If this is a new setup, start qqX, check the settings & then install a basic Linux distro, one that you are familiar with perhaps, which will tell you if your setup is okay.

When you know that everything is working correctly, you can start exploring ...

qqX will auto-detect if new releases are later available & quietly prompt for updates.

Use the installer to update, reinstall, uninstall or reconfigure.

## Release notes

Now in official release. Testing has been carried out on a variety of mainstream distros.

Both the release candidate & the beta versions have been consistently safe & stable.

All scripts have been carefully Shellcheck linted & have full error handling routines.

qqX always makes backups, as is *standard good practice* with *any* software.

Feedback, positive or constructive, at <https://discord.gg/sNmz3uw>

## why 'X'

More technically speaking qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X'

But traditionally Linux uses the X window system from X.org, so 'X term' often gets used as shorthand ...

<https://en.wikipedia.org/wiki/X_Window_System>

<https://en.wikipedia.org/wiki/Wayland_(protocol)>
