# What is Turbulence-Evolution?

Turbulence is an utility similar to Chakra's kapudan, that
configures multiple aspects of Openbox and KDE Desktop at 
first boot. Some of it's features are:

* Sleak grey graphical layout
* Provides information of Manjaro to new users
* Can allow the user to easily select which Folders he wants in his home directory
* Allows users to select which placement for their tint2 (OpenBox)
* Allows users to select which wallpaper they want (Openbox/KDE)
* Allows users to select what packages they want and don't want (OpenBox only for now.)
* Can also allow people to open system settings after they've ran through everything else to set any last minute details

# How to install Turbulence-Evolution

To install Turbulence, just run the following commands.

```
git clone http://git.manjaro.org/community/turbulence.git turbulence
cd turbulence
chmod +x install.sh
sudo bash install.sh
```

# How to remove Turbulence-Evolution

To remove Turbulence, just `cd` to the turbulence directory and run the following command.

```
sudo bash install.sh -r
```

# TODO

* Add better language support (very soon)
* Merge this project and Turbulence-Evolution (Also very soon)
* Add package selection support
* Add much more general support for other settings