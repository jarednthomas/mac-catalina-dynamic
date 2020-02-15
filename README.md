# mac-catalina-dynamic
Dynamic wallpaper that changes throughout the day.

### Installation
Change directory to your Pictures folder.
```sh
$ cd Pictures
```

Create a wallpapers directory if it doesn't exist already.
```sh
$ mkdir wallpapers
```

Clone this repo into "wallpapers" (/home/<user>/Pictures/wallpapers).
```sh
$ cd wallpapers
$ git clone https://github.com/jarednthomas/mac-catalina-dynamic
```

Fix paths to images in xml file by replacing user path (/home/jared/) with your username. Ex; jared to nathan:
```sh
$ sed -i 's/jared/nathan/g' catalina_dynamic.xml
```

Set background to xml file.
GDM Steps: Tweaks > Appearance > Background > Select XML File
