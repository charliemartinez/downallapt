# downallapt
Download all .deb packages from an apt repository

Author: Charlie Martínez <cmartinez@quirinux.org>
GPLv2 License - https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

## How it works:

Download all the files from the repositories
that are enabled in /etc/apt/sources.list and /etc/apt/sources.list.d
and save them in a new / packages folder

## Instructions:

Comment those repositories in /etc/apt/sources.list and /etc/apt/sources.list.d that we do not want to download.

Run as root:

chmod 755 downallapt
mv downallapt /usr/local/bin/downallapt
downallapt
