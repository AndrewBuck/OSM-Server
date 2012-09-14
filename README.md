This is a readme file for the OSM-Server git repository.

This git repository is used to track script and config file changes on the
OSM-Server virtual machine environment.  This repository is set up a little bit
differently than a normal source repository would be.  The config files tracked
by this repository are all over the filesystem, so the repository is created
right at / on the VM image.  You can check out this repository on another
machine into a subdirectory somewhere to edit the scripts if you like, but do
not copy the scripts to / or check the git repo out at / as it could overwrite
files on your own system.

