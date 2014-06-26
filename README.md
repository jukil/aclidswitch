# aclidswitch
Change systemd's lid switch action depending on the laptop's AC state

# Installation
Configure `default/aclidswitch` and set your desired actions for 
`LID_SWITCH_ACTION_BAT` and `LID_SWITCH_ACTION_AC` depending on the
AC state. The default settings are `suspend` on battery and `ignore` on 
AC. Possible settings are:

* `suspend`
* `hibernate`
* `ignore`
* `poweroff`
* `reboot`
* `halt` 
* `kexec`
* `hybrid-sleep`
* `lock`

Place `default/aclidswitch` in `/etc/default`, `60-aclidswitch.rules` 
in `/etc/udev/rules.d` and `aclidswitch` in `/usr/bin`.

## Arch Linux
Arch Linux users can also install the package from the AUR 
[here](https://aur.archlinux.org/packages/aclidswitch/).
