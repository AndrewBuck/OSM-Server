Welcome to the OpenStreetMap Virtual Machine.


This VM image is set up to easily allow you to quickly set up server to serve tiles for maps, resolve address and reverse address lookups.

To begin the process of downloading data and setting up the server double click "Start Configuration Wizard" on the Desktop (click "Run in Terminal" in the window that pops up).

This will walk you through the server setup process.  Most of it is just informational dialog boxes telling you what the script will do and how long it will likely take to run, but there are currently 4 points where your input will be required.  They are as follows.

 *  A web browser will be loaded and you will be taken to the Geofabrik extract site.  You should either download the extract you want from this site in PBF file format, or load/download the data from another source by copying the PBF files onto the desktop.  After that is finished closing the webbrowser will automatically continue the install process.

 *  You will be asked whether or not you want to download coastlines.  You need these if you plan to render tiles, or run a tileserver, but not if you only want Nominatim.

 *  You will be asked if you want to import your extract into a rendering database and set up a tileserver.

 *  You will be asked whether you want to set up a Nominatim database and website.  (The website is already set up actually, but will give an error message until it has an extract loaded into the DB)
 
 
 
  *** SPECIAL NOTE: Although some of the instructions indicate you may import multiple extracts at once, currently the VM has only been tested with a single extract and will probably fail if you try multiple ones at once.  You can manually merge your extracts with osmosis and just leave a single combined extract file on the desktop as a temporary workaround to this.
