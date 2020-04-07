ok screw all that exposition

QUICK DESCRIP BRO
ARCHLINUX DISC

COMES WITH ...KINDA OLD ENLIGHTENMENT BUT ITS NEAT I SUPPOSE
PROBABLY FIREFOX AND A TERMINAL
JUST CRAP YOU NEED TO BE A BIT MORE COMFY INSTALLIN ARCHIE BOI

but heres the thing it had way too much crap in it for its intended purpose
it was fun to make and neat to use as an alternative to regular arch isos

but without one built its not even worh building one (to me) so i'm just gonna leave all this here incase anybody wants to try it or find out wtf it was,before it gets wiped out later.

i think i'd like to revisit this idea with a much simpler setup later maybe. BIG maybe. i mightnot give any craps about this in a few days yanno

but these directions should get you all set if youve got the archiso stuff installed and if youc ant figure it out

well i put about 5 mins into sorting it out before deciding naaaw. so good luck and um. enjoy the downtime, efl is kinda big 
## Building it!
Currently this is built using [archiso](https://wiki.archlinux.org/index.php/archiso). This means that i've youve got Arch, possibly even similar forks of Arch, you can build this iso yourself quickly and easily. It may be helpful to refer to the article linked above, too.

1. Clone this repository somewhere, something like `git clone https://github.com/steakwipe/tranquility.git`
2. cd into the `tranquility` directory `cd tranquility`
3. create the output directory, `mkdir out`
4. and finally build it using the convenient script. `./build.sh -v`

The process uses Arch's pacstrap tool (which you may recognize from doing your own installs) to retrieve our package list, and "install" the packages into this directory, does all the configuring magic, squashes the whole deal up nicely, and sticks a shiny isolinux on top to boot it.

It'll boot on EFI and Legacy BIOS systems, as well. We'll try to keep a recent build of the iso itself accessible, but for best results grabbing a build will always be a good bet, if you have Arch-flavor tools handy. 

I DONT GO ON IRC ANYMORE WHO CARES




