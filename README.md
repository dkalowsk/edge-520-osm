# edge-520-osm
Open Street Maps for Garmin Edge 520

This repo contains a series of map files created for the Garmin Edge 520 based
off of files generated from the http://garmin.openstreetmaps.nl website.

This is basically a mirror so that I don't have to re-request the image file
every time.  Since it's git, updates can be provided.

Installation instructions:
- Attach your Garmin Edge 520 to your computer.  It should mount as a storage
  device to computer as a DOS/Fat filesystem.
- Open the Garmin directory
- Copy the gmapbmap.img to your local computer as a backup
- Copy the gmapbmap.sum to your local computer as a backup
- Select the updated map file you want from this repo
- Rename it to gmapbmap.img
- Copy to your Garmin Edge 520 in the /Garmin/ directory
- Unmount the Garmin Edge 520 from your computer
- Reboot the Garmin Edge 520.


Naming conventions of the file(s):
  $SECTION-$STATE-gmapbmap.img

For example:
  nw-or-gmapbmap.img is the file for Northwestern Oregon
