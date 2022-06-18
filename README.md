# rog-tame

Most of the credit goes to
[this reddit post](https://www.reddit.com/r/FlowX13/comments/t32gra/how_to_gain_even_more_control_of_your_flow_x13/).

Tried to make an interface to what the batch files do.

## Warnings

1. I am not responsible to what you do to your computer, this is a tool that
I use for myself and I am nicely sharing it with the world
2. Make every executable that this tool is running only writable by an
administrator, otherwise you're jeopardizing the security of your computer.

## Installing

1. Install [atrofac-cli](https://github.com/cronosun/atrofac/tags) and write
down the path where `atrofac-cli` is
2. Install [powermode](https://github.com/AaronKelley/PowerMode/releases) and write
down the path where `powermode.exe` is
3. Install [ryzenadj](https://github.com/FlyGoat/RyzenAdj/releases) and write
down the path where `ryzenadj.exe` is
4. Install this folder somewhere in your hard drive, I'd recommend
`C:\Program Files`. Please read the warning number 2 again if you didn't yet.
5. Make sure `sh` is available. If you don't have it installed I recommend
[BusyBox for Windows](https://frippery.org/busybox) and rename the file to
`sh.exe`.

## Usage

Open a powershell with admin privileges and run the command (change depending
on where your executables are):

```ps1
& "C:\Program Files\rog-tame\sh.exe" "C:/Program Files/rog-tame/rog-tame" silent
```

for the silent profile or:

```ps1
& "C:\Program Files\rog-tame\sh.exe" "C:/Program Files/rog-tame/rog-tame" turbo
```

for the turbo profile.

You can create aditional profiles by renaming any file in the `plans` folder
and adjusting to your taste.




