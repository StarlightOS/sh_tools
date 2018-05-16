HOW TO BUILD STARLIGHT OS

1 - Start with mini.iso from https://help.ubuntu.com/community/Installation/MinimalCD
2 - Install only the bare system tools
3 - Boot and run xfceslim
4 - Create the dist installer with bodhibuilder
5 - Unpack filesystem.squashfs from the casper folder
6 - Run xfceinside inside the squashfs-root folder
7 - Compress squashfs-root into filesystem.squashfs again
8 - Move filesystem.squashfs inside the CD folder from https://github.com/StarlightOS/cd_folder
9 - Compile the cd with the script from the Commands file: https://github.com/StarlightOS/sh_tools/blob/master/commands
10 - Done
