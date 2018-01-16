# tranquility
Enlightenment meets Arch!
---
Latest build available via Mega: https://mega.nz/#!GFUHyDzK!15hR77aoDc3oQn5bspPZ4NmFQKf2sW5NyvmsMVvcx_c
Built Jan. 16, 02:31 PST
---
Tranquility is an Archlinux-based live ISO with a recent build of Enlightenment sitting neatly on top. Currently, this image is analogous to the Archlinux install media, except it boots directly to an Enlightenment desktop. 

Currently, it only includes Xorg support, but it's probable we'll get Wayland going on it sooner or later- E is great on Wayland so it's hard to resist.

The software selection available is a basic setup of E, Terminology for your term, Firefox Developer Edition so you can look at the Arch install docs on the same machine for once, and others. The selection will very likely fluctuate over time as we refine the desktop experience and continue adding functionality.

Terminology will ride on top of a fantastic ZSH setup by my dear friend [SpaceToast](http://github.com/5paceToast/) and her magic coding powers. [toasty-zsh](http://github.com/5paceToast/toasty-zsh) is fantastic, and you should check it out too.

Because I'm a sucker for a super-fly prompt, Tranquility trades the prompts typically included with toasty-zsh or others, in favor of [Powerline-go](https://github.com/justjanne/powerline-go). Especially with all this git-fu we're doing with this repo, it's been poretty nice, so naturally it came along for the party!

Myself, I am not a particularly experienced or talented programmer, but I do like pretty, useful things, and I do like putting them together. With the help of some friends, we're trying to put together a fantastic Enlightenment experience, as a springboard onto a solid Arch install. Plenty more to come- I have a habit of spamming commits. :P

## Building it!
Currently this is built using [archiso](https://wiki.archlinux.org/index.php/archiso). This means that i've youve got Arch, possibly even similar forks of Arch, youc an build this iso yourself quickly and easily. It may be helpful to refer to the article linked above, too.

1. Clone this repository somewhere, something like `git clone https://github.com/steakwipe/tranquility.git`
2. cd into the `tranquility` directory `cd tranquility`
3. create the output directory, `mkdir out`
4. and finally build it using the convenient script. `./build.sh -v`

The process uses Arch's pacstrap tool (which you may recognize from doing your own installs) to retrieve our package list, and "install" the packages into this directory, does all the configuring magic, squashes the whole deal up nicely, and sticks a shiny isolinux on top to boot it.

It'll boot on EFI and Legacy BIOS systems, as well. We'll try to keep a recent build of the iso itself accessible, but for best results grabbing a build will always be a good bet, if you have Arch-flavor tools handy. 

If you want to say hi you can often find us hanging out in #e on irc.freenode.net!




