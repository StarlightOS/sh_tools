HOW TO BUILD STARLIGHT OS<br>
<br>
1 - Start with mini.iso from https://help.ubuntu.com/community/Installation/MinimalCD<br>
2 - Install only the bare system tools<br>
3 - Boot and run xfceslim<br>
4 - Create the dist installer with bodhibuilder<br>
5 - Unpack filesystem.squashfs from the casper folder<br>
6 - Run xfceinside inside the squashfs-root folder<br>
7 - Compress squashfs-root into filesystem.squashfs again<br>
8 - Move filesystem.squashfs inside the CD folder from https://github.com/StarlightOS/cd_folder<br>
9 - Compile the cd with the script from the Commands file: https://github.com/StarlightOS/sh_tools/blob/master/commands<br>
10 - Done
