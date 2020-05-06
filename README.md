# ovlSysmodule - ReiNX Support

A Tesla overlay that allows you to toggle sysmodules on the fly that now works on ReiNX

## Installation

Download the latest ovlSysmodules.ovl from the release page and drop it into the /switch/.overlays folder on your Switch's SD card

If a specific sysmodule does not work it is most likely missing the toolbox.json file in the /contents/ directory.

Assuming that the sysmodule is compatible and can be disabled/enabled you can make the .json file yourself if it is not readily available (most sysmodules come with the .json file however)

```sh
{
	"name"  : "NAME-OF-SYSMODULE",
	"tid"   : "TITLE_ID_HERE",
	"requires_reboot": true_OR_false_here
}
```

As an example

```sh
{
	"name"  : "poopoopeepee",
	"tid"   : "6900000000000420",
	"requires_reboot": false
}
```
