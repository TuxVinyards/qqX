# qqX  - quickemu quickget X terminal project

![qqX-vmm](https://github.com/TuxVinyards/qqX/assets/3956806/18e5c495-8072-49a5-8b9c-e1302549efcf)

- Improves on Quickemu's very basic front-ends for [Qemu / KVM](https://qemu.readthedocs.io)

- More up-to-date and easier to mod than Gnome Boxes.

- Much easier than the complex Qemu front-ends based on LibVirt.

## [Latest release 1.10.01](#release-notes)

Large code update with lots of new features and Quickemu improvements.

An extended testing program has now added extra handling routines for KDE 6, XFCE and LXQT

- MacOS remains [much faster](https://github.com/TuxVinyards/qqX/wiki/Mac-OS) in qqX and Windows languages are now sorted.

- The qqX coding hot-swap has been refined and FreeSpirit has the latest updates and community PR's.

- qqX's quickget now lets you scroll backwards and forwards between the different distro info pages.

- You can also scroll up and down between releases and editions and swap around your choices.

- The downloader tells you the download size and checks the link for viability.

- The option to boot from ISO for disk management has been further polished

- Folders can now be sym-linked between each other to help organize.

More in the [release notes](#release-notes) and wiki to follow in the next few days

### Simple and Straightforward

- A complete menu system within a unique Linux hybrid interface.

- Simple list browse, download, and organise countless distros

- Easy install Virtual Linux, Windows and MacOS. Plus others.

- Multiple display modes, utilities, optimizers and tools

![new -vm-selector-qqX](https://github.com/TuxVinyards/qqX/assets/3956806/42a4b480-4d7d-47fe-91f5-0069fa1511a8)

Easy _install the latest_ and greatest.

![qqX-mouse-click-iso](https://github.com/TuxVinyards/qqX/assets/3956806/ae6c9fe1-0c46-4e05-b75a-b6964f35bad2)

_No need to wait_ for Quickget to add in the distros or releases that you want.

![qqX-mouse-conf-open](https://github.com/TuxVinyards/qqX/assets/3956806/76a2431b-0573-4fb7-961b-3aa048ea2ca2)

Start specific VM's straight from the folder

### Get the latest fixes

No need to wait for Quickemu bug fixes to make their way through the system either. Any new input from the quickemu community can be put to work.

- Easy [installation](#how-to-install)

- Always up-to-date text [translation](https://github.com/TuxVinyards/qqX/wiki/Translation)

## Screenshots and features

Release 1.1.03 improved the _main menu_ & added a gtk display option, whilst 1.5.02 added GL toggle:

![ubuntu-qqX-zsync](https://github.com/TuxVinyards/qqX/assets/3956806/c3104e5d-c008-4dbc-9666-42d13d2af357)

Release 1.5.02 added _alphabetical zooming_ into list sections for the Quick Get multi distro menu:

![alpha-zoom-qget](https://github.com/TuxVinyards/qqX/assets/3956806/bfde0aef-9094-443d-a11d-5bd6745e5702)

Release 1.7.01 added a choice of 5 _menu styles_ and of  [Custom Menus](https://github.com/TuxVinyards/qqX/wiki/Custom-Menus) and 1.7.03 added:

- A _handy distro rename function_ which helps with upgrades and will update all the .conf internals in one click.

Release 1.6.02 introduced [custom boot parameters](https://github.com/TuxVinyards/qqX/wiki/Custom-Qemu-boot-parameters) and the ability to run [Arm64, Risc-V +](<https://github.com/TuxVinyards/qqX/wiki/Custom-Machine-Types>)

Whilst earlier releases added:

- Distro homepage browser and link checker
  
- Configuration tune-up wizard

- Boot up Screen sizing (default & individual)

- Multiple snapshot management, including of shared disks.

- A days count on 'daily-live' ISO's

- Qcow2 repair, resize and diagnostics

- Secondary storage creation

![Screenshot at 2023-02-22 12-59-04-1920](https://user-images.githubusercontent.com/3956806/220619057-f63883d2-4d0d-4130-94e1-d444f1567be4.jpg)

## How to Install

Start from scratch. Or safely test out the qqX difference on your existing VM's.

- From version 1.8 onwards, the installation of quickemu is not essential but qqX has been designed to work happily alongside quickgui or any quickemu shortcuts, if you already have them.

  Normal [Filesystem_Hierarchy_Standard](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard) Linux is generally expected.

  No further software, support structures or dependencies should be needed.

- See the installer [wiki](https://github.com/TuxVinyards/qqX/wiki) for more details

## Release notes

- @ Sept 1 - Version 1.10.01  

- Adds Windows languages and sorts the Quickemu problems too. You can now download French, not just 'French Canadian' for example.
  
- There's an improved distro editions selection mechanism which allows you to scroll up and down between releases and editions, depending on what you find and how you decide.

- Other features also include being able scroll through the distro info pages, and from any given start point.
  
- And finally some control over boot management and being able to select whether we boot from the virtual hard drive or from the ISO. Very useful for partition management and disk maintenance.

- You can now organize folders by various categories. The _same_ machine can now be listed in two or three folders at once. All by the magic of 'symbolic links'.  Expect a wiki page shortly to explain in full detail.

- The ability to download any given Linux ISO and install it, has had a make over as well.

- This release has had extra extensive testing, ranging from the slickness of 'Garuda Dr460nized' to the lightness of LXQT

- FreeBird is default and based on quickemu @ Aug 4.  FreeSpirit has had initial testing and looks good. This is based on Aug 29.

- Users still on version 1.8.04 and previous should download the latest release directly. For others, there was a fix in place a while back for the github changes behind the wget 302 / SHA error. So, use the installer/updater ....

- The qqX latest release is available [here](https://github.com/TuxVinyards/qqX/releases/latest) but you can also download via the **code/clone** button. The 'dev' branch may be newer and may have the very latest tweaks and bug fixes too ...

### Reliability

- Testing is always carried out on a variety of mainstream distros before release. (more so on 1.10)

- All scripts are carefully Shellcheck linted & have full error handling routines.

- qqX always makes backups, as is _standard good practice_ with _any_ software.

### Improvements

- Tests show that _official_ Quickemu 4.9.5/6 can cause Intel processors to run MacOS very slowly. This doesn't affect FreeBird or FreeSpirit.

- Also the Quickemu problem, where telescoped/nested VM grind to a halt, doesn't happen when using the qqX builtins either.

- As qqX will offer a config autotune after a download, the Quickemu issue [#1387](https://github.com/quickemu-project/quickemu/issues/1387#top) with Windows will not be present.

See [FreeBird](https://github.com/TuxVinyards/qqX/wiki/FreeBird) wiki page for details on the built-ins, or [change log](https://github.com/TuxVinyards/qqX/wiki/Change-Log) for a history synopsis

### FAQs and Help

- Lots available in the [qqX wiki pages](https://github.com/TuxVinyards/qqX/wiki/FAQs-and-Help)

For general Quickemu problems, there is a chat forum at <https://discord.gg/sNmz3uw>

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

For me, qqX is something to do when it's too hot or it's raining and I can't be outside. So, Linux development amongst the Vinyards, with the Olde English spelling of " Vine Yards " which doesn't have with an 'e', to match the context.

1533 (1651 pub.), Henry Cornelius Agrippa, De Occulta Philosophia
...therefore they who are more religiously and holily instructed, neither set a tree nor plant their _**vinyard**_, nor undertake any mean work without divine invocation...

## why 'X' ?

Traditionally Linux has used the X window system from X.org, so 'X term' often gets used as shorthand for the terminal.

More technically speaking qqX runs in a 'terminal emulator' and can also run with Wayland display systems as well as with 'X' ...

<https://en.wikipedia.org/wiki/X_Window_System>

<https://en.wikipedia.org/wiki/Wayland_(protocol)>
