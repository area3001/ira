# Ira Commandline Interface

# Getting Started
```shell
# set pixel length of specific device
./ira config set <dev> pixel_length 150

# enable fx mode for a specific device
./ira fx enable <dev>

# list available fx's
./ira fx list

# set specific fx for a specific device (colors are hex3 (rgb) or hex 6 (rrggbb)
./ira fx set <dev> 2 fg=f0f bg=0f0

# ask devices to send a hearthbeat (best to do before listing)
./ira devices sync

# list devices
./ira devices list

# reset a device
./ira devices reset

# set the name of a device
./ira config name <dev> <name>
```