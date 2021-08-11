# ativ9pctl

A script for controlling some low-level functionality
on a Samsung Ativ 9 Book Pro laptop.

## Use case

This is a script for getting some of the functionality
back from my laptop's function keys when running under
a lightweight GUI.

Remap keys or chords in your display manager config
or remapper of choice to fire off this script.  Use
the following arguments to get the desired functionality
back.

Feel free to repurpose this for your own filthy aims.
As always, *use at your own risk.* 

## Usage

Before you use the script, be sure to set your username
in the __ATIV_USER__ variable inside the script.

__NB__ that changing the brightness and using suspend both
require elevation (i.e., sudo).

```
Options:
        -v --verbose
            Increase verbosity level

Actions:
        -b --brightness [number]
            Increase screen backlight brightness by
            [number] (this can be a negative number,
            minimum is 1, maximum is ~900)

        -l --volume [number]
            Increase currently selected mixer volume by
            [number] (this can be a negative number)

        -s --suspend
            Put the laptop to sleep
```

For slightly more info, read the script, duder.
