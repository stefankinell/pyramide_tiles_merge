# pyramide_tiles_merge
A windows powershell script that can merge overlapping sets of pyramid tiles with the help of ImageMagick

The intended use for this script is if you have two set of tiles for e.g. use with leaflet.js that are overlappning. Then this script can be handy to merge the images that are in the border between the two sets of tiles.

The method is to compate the two sets of folders, list the files that exists in both and then use ImageMagick tool to merge the two into one.
