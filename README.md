# tranquility
Enlightenment ...met Arch.
---
keepin isos of this offsite was fucky, weird, and fishy lookin tbh. since i cant fit thie iso on gh right now, you'll have to build it i'm afraid. probably won't be around much longer though, considering a simpler rebuild. this was a bit excessive.
---
*CURRENTLY*
Tranquility is an Archlinux-based live ISO with a pretty dam old build of Enlightenment sitting neatly on top. Currently, this image is analogous to the Archlinux install media, except it boots directly to an Enlightenment desktop. 

Basically just has some simple wares on top of E for a low overhead desktop to install your Arch or whatever with. TURNED OUT A LITTLE BLOATY FOR REALISTIC USES THO

Terminology is pretty nice though. it currently will ride on top of a fantastic ZSH setup by my dear friend [SpaceToast](http://github.com/5paceToast/) and her magic coding powers. [toasty-zsh](http://github.com/5paceToast/toasty-zsh) is fantastic, and you should check it out too. I don't spin up a new system without it. it's definitely the only thing that's going to survive this remake.

oh yeah i powerlined the prompt too but that was also a bit much for a freakin installbase disc wtf steak

this last little paragraph basically said i'm an idiot but i like UX. this is still true

## Building it!
Currently this is built using [archiso](https://wiki.archlinux.org/index.php/archiso). This means that i've youve got Arch, possibly even similar forks of Arch, you can build this iso yourself quickly and easily. It may be helpful to refer to the article linked above, too.

1. Clone this repository somewhere, something like `git clone https://github.com/steakwipe/tranquility.git`
2. cd into the `tranquility` directory `cd tranquility`
3. create the output directory, `mkdir out`
4. and finally build it using the convenient script. `./build.sh -v`

The process uses Arch's pacstrap tool (which you may recognize from doing your own installs) to retrieve our package list, and "install" the packages into this directory, does all the configuring magic, squashes the whole deal up nicely, and sticks a shiny isolinux on top to boot it.

It'll boot on EFI and Legacy BIOS systems, as well. We'll try to keep a recent build of the iso itself accessible, but for best results grabbing a build will always be a good bet, if you have Arch-flavor tools handy. 

I DONT GO ON IRC ANYMORE WHO CARES




