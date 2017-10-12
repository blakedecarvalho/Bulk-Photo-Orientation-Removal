# Bulk-Photo-Orientation-Removal
For people that have a massive directory of images (ie 30,000+) and want to quickly delete or remove any images that aren't of a certain orientation type (aka landscape vs portait) with a crap pc

# WHAT THIS SCRIPT IS FOR:
For people that have a massive directory of images (ie 30,000+) and want to quickly delete or remove any images that aren't of a certain orientation type (aka landscape vs portait) with a crap pc

# BEFORE USE:
-Make sure all images are in a singular format (such as all jpg or png).  Free software I recommend is Bulk Image Converter from sourceforge.  You could also just search ".gif" and delete all results.
-Number all images numerically (examples: 1.jpg to 50000.jpg) which can be done using the free software Bulk Rename Utility
-Pick the correct script for use, they are named accordingly.
-Change the number in the script equal to the first image number (ie put 1 for 1.jpg)
-Change the number after "-le" to the last image number

# TO CREATE AN EXECUTEABLE VERSION (of a bash script) FOR NEWCOMERS:
1) cd to the location of choice,
2) open nano
3) input script
4) save

# AUTHORS NOTE: 
Advanced users may notice that you could achieve this without numbering all images and simply using the "for i in *.jpg;" command, but that loads all filenames into a cache.  If you have 80,000 images in a single directory, it can cause freezing.  Using the numbering method forces the PC to do one line at a time.
