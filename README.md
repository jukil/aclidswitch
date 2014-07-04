# aclidswitch
Simple Power Management tool to be used supplementary to
[TLP](https://github.com/linrunner/TLP).
* Change systemd's lid switch action depending on the laptop's AC state
* Define an action on low battery capacity
* Set different brightnesses for battery and AC 

# Installation
Configure `default/aclidswitch` and set your desired actions 
Place `default/aclidswitch` in `/etc/default`, `60-aclidswitch.rules` & 
`99-low-battery-action.rules` in `/etc/udev/rules.d` 
and `aclidswitch` in `/usr/bin`.

## Arch Linux
Arch Linux users can also install the package from the AUR
[here](https://aur.archlinux.org/packages/aclidswitch-git/).

# Feedback
I am very happy to listen to feedback. File an issue or write me an email to
orschiro aet gmail dod kom.
