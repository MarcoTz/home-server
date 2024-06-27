# Hosting

## Highest Priority 

### Plex 

Already running, setup should stay very similar.
Host needs access to all hard drives in the bay.
Hard drives should be automounted, but bay keeps changing UUIDS

Either figure out how to still automount 
Or make sure hard drives never get removed 

### Remote Access 

Either SSH or alternatives such as TrueNAS dashboard etc need to be available for monitoring and troubleshooting
Preferably also available outside network

### Firewall

Anything open to the internet needs to be secured
This might automatically be included depending on the setup

## High Priority 

### Telegram Bots 

Currently only Plant Bot is important.
Possibly who-is-watching bot as well.
additional bots might be added later

### Web Hosting 

Plant Website, Recipe Website should both be up
Preferably available outside the network, otherwise wireguard might be fine.
They also need CI whenever pushes show up.
Maybe the websites can also be rewritten to not use the gh-pages workarounds

### Reverse Proxy 

Different things might be hosted on different devices, so I might need to correctly assign requests.
Also, security 

## Medium Priority 

### Jellyfin

Will be used for ebooks mostly since plex handles video.
Alternative is also possible (maybe nextcloud can replace it) 

### Nextcloud 

Files backup and sync between devices 
Especially for replacing google photos
Needs to be available from outside the network

## Low Priority

### Git Server 

Host personal repos (plants/recipes/etc) on home server 
needs to be available from outside the network

### DNS

Some way to keep access when IP address changes
