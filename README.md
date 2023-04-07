# linphone-fix
linphone open browser link sip/tel auto call (xdg-open)
Tested on Linux Mint 20, Ununtu 20.04, Ubuntu 16.04

## install
``apt install linphone``

copy files your linux home dir and

``chmod 755 ~/.local/bin/linphone-fix``

## rebuild

``update-desktop-database``

## debug
uncomment last line in file ~/.local/bin/linphone-fix

``tail -f /tmp/linphone-fix.log``
