# aclidswitch
Simple Power Management tool that can be used supplementary to
[TLP](https://github.com/linrunner/TLP) to provide the following functionality:

* **Custom lid actions.** If running on battery, turn your laptop into standby when the lid is closed. If the laptop is charging, then do nothing.
* **Low battery action.** Put your laptop into hibernation if the battery reaches a critically low level.
* **Custom brightness.** Set different brightness levels for battery and AC use.
* **Custom display management (DPMS) settings**: Disable DPMS on AC or change the blanking times on battery.

# Installation
Place the following files as follows in your file systemL

```
default/aclidswitch ➡ /etc/default
98-aclidswitch.rules ➡ /etc/udev/rules.d
99-low-battery-action.rules ➡ /etc/udev/rules.d
aclidswitch ➡ /usr/local/bin
```

Make the script executable: `chmod +x /usr/local/bin/aclidswitch`.
Configure `/etc/default/aclidswitch` and define your desired settings.

## Arch Linux
Arch Linux users can also install [the package](https://aur.archlinux.org/packages/aclidswitch-git/) from the AUR.

# Feedback
I am very happy to receive your feedback. File an issue or write me an 
email with my Github username at Gmail.
